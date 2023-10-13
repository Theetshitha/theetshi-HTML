# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Very Dark Blue: hsl(243, 87%, 12%)
- Desaturated Blue: hsl(238, 22%, 44%)

### Accent

- Bright Blue: hsl(224, 93%, 58%)
- Moderate Cyan: hsl(170, 45%, 43%)

### Neutral

- Light Grayish Blue: hsl(240, 75%, 98%)
- Light Gray: hsl(0, 0%, 75%)

## Typography

### Body Copy

- Font size (paragraph): 16px

### Fonts

#### Headings, Call-to-actions, Header Navigation

- Family: [Raleway](https://fonts.google.com/specimen/Raleway)
- Weights: 400, 700

#### Body

- Family: [Open Sans](https://fonts.google.com/specimen/Open+Sans)
- Weights: 400
@media(max-width:375px){
    body{
        margin: 0;
        padding: 0;
        width: 100%;
        font-family: 'Open Sans', sans-serif;
        font-size: 16px;
        cursor: pointer;
        color:hsla(0, 2%, 10%, 0.664);
       
    
        
    }
    
    h1,h4,h5,h6{
        font-family: 'Raleway', sans-serif;
        color: hsl(243, 87%, 12%);
    }
    
    .main{
        width: 100%;
        display: flex;
        flex-wrap: wrap;
        align-items: center;
        justify-content: center;
    }
    
    .navbar{
        
        display: flex;
        justify-content: space-between;
        align-items:center ;
        width: 90%;
        flex-wrap: wrap;
        height: 150px;
        
    }
    
    .navbar ul{
        display: flex;
        flex-wrap: wrap;
        gap: 40px;
    }
    
    ul a{
        text-decoration: none;
        color:hsla(0, 2%, 10%, 0.664);
        font-weight: 400;
    
    }
    .home1{
    
        width:100% ;
        background-image: url(/images/bg-curve-desktop.svg);
        background-repeat: no-repeat;
        background-size: contain;
    
    }
    .page1{
    
        width: 95%; 
        display: flex;
        justify-content:center;
        flex-wrap: wrap;
        align-items: center;
        margin: 3%;
        padding-bottom: 15%; 
        /* padding-left: 4%; */
        /* padding-top: 8%; */
      
    }
    
    .page1-inner{
        width: 50%;
    }
    .page1-img1{
        width: 50%;
        text-align: center;
    }
    .page1-img1 img{
        width: 80%;
    }
    
    
    .page1-inner h1 {
        width: 87%;
        line-height: 40px;
    }
    
    .page1-inner p {
        width: 88%;
        line-height: 30px;
    }
    .page1-inner form{
        display: flex;
        flex-wrap: wrap;
        gap: 20px;
    }
    
    .page1-inner input{
        width: fit-content;
        padding: 2% 6%;
    }
    .page1-inner button{
        width: fit-content;
        padding: 2% 7%;
        background-color: hsl(224, 93%, 58%);
        color: white;
        font-weight: bold;
    }
    
    .home2{
    
        width:100% ;
        background-image: url(/images/bg-curve-desktop.svg);
        background-repeat: no-repeat;
        background-size: contain;
    
    }
    .page2{
       
        width: 95%; 
        display: flex;
        justify-content:center;
        flex-wrap: wrap;
        align-items: center;
        margin: 3%;
        padding-bottom: 8%; 
        /* padding-left: 4%; */
        /* padding-top: 8%; */
      
    }
    
    .page2-inner{
        width: 50%;
    }
    .page2-img1{
        width: 50%;
        text-align: center;
        margin-bottom: 4%;
    
    }
    .page2-img1 img{
        width: 80%;
        margin-bottom: 4%;
    
    }
    .page2-inner h1 {
       
        margin-bottom: 6%;
    
    }
    .page2-inner p {
        width: 86%;
        margin-bottom: 4%;
    
    }
    
    .page2-inner span{
       color:hsl(170, 45%, 43%);
       text-decoration-line:underline;
    }
    
    .page2-middle{
        padding-left: 4%;
        box-sizing: border-box;
        width: 70%;
        height: fit-content;
        background-color: white;
        border: none;
        cursor: pointer;
        box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
        margin-bottom: 3%;
    }
    .page2-author{
        display: flex;
        gap: 5px;
        justify-content: space-around;
        align-items: center;
        flex-wrap: wrap;
        width: 80%;
        height: 10%;
    }
    .page2-middle p {
        width: 90%;
    }
    .page2-author1 img{
        width: 80%;
        object-fit: cover;
        border-radius:50%;
    }
    .page2-author2 {
        width: 100%;
       
    }
    .footer{
        display: flex;
        flex-direction: column;
        justify-content: center;
       flex-wrap: wrap;
    }
    
    .footer-nav1{
        display: flex;
         align-items: center;
        justify-content: space-evenly;
        gap: 0px;
       
        flex-wrap: wrap;
        color: white;
        background-color:  hsla(240, 22%, 44%, 0.89);
       
    }
    .footer-nav1-1{
        width: 50%;
        margin:5%;
    }
    
    .footer-nav1-1 p {
        width: 85%;
    }
    
    .footer-nav1-2 form{
        display: flex;
        flex-direction:column ;
        gap:20px ;
    }
    .footer-nav1-2 {
        width: 50%;
        
    }
    .footer-nav1-2 input {
        width: fit-content;
        padding: 2% 20%;
    }
    
    .footer-nav1-2 button {
        width: fit-content;
        padding: 2% 7%;
        background-color: hsl(224, 93%, 58%);
        color: white;
        font-weight: bold;
    }
    .footer-nav2{
        display: flex;
        align-items: center;
       justify-content: space-evenly;
       flex-wrap: wrap;
       gap: 20px;
      
       flex-wrap: wrap;
       color: white;
       background-color:  hsl(243, 87%, 12%);
      
    }
    .footer-nav2 a{
        text-decoration: none;
        color: white;
    }
    .footer-nav2-1{
        display: flex;
        flex-direction: column;
        gap: 10px;
        width: 29%;
        margin:9%;  
    }
    .footer-nav2-2{
        display: flex;
        flex-direction: column;
        gap: 10px;
        width: 25%;
        margin:3%;
    }
    .footer-nav2-3{
        display: flex;
        flex-direction: column;
        gap: 10px;
        width: 25%;
        margin:3%;
        padding-bottom: 3%;
    }
    .footer-nav2-4{
        display: flex;
        gap: 10px;
        flex-wrap: wrap;
        width: 22%;
        margin:3%;
        padding-bottom: 7%;
        
    }
    .footer-nav2-4 i{
        border: 1px solid white;
        padding: 4px;
        border-radius: 50%;
    }
    
    .footer-nav2 a:hover{
        color: aqua;
    }
    
    
    button:hover{
        background-color: white;
        color: black;
        cursor: pointer;
    }
    
}


-----------------------------------------------
body{
    margin: 0;
    padding: 0;
    width: 100%;
    font-family: 'Open Sans', sans-serif;
    font-size: 16px;
    cursor: pointer;
    color:hsla(0, 2%, 10%, 0.664);
   

    
}

h1,h4,h5,h6{
    font-family: 'Raleway', sans-serif;
    color: hsl(243, 87%, 12%);
}

.main{
    width: 100%;
    display: flex;
    
    align-items: center;
    justify-content: center;
}

.navbar{
    
    display: flex;
    justify-content: space-between;
    align-items:center ;
    width: 90%;
   
    height: 150px;
    
}

.navbar ul{
    display: flex;
       gap: 40px;
}

ul a{
    text-decoration: none;
    color:hsla(0, 2%, 10%, 0.664);
    font-weight: 400;

}
.home1{

    width:100% ;
    background-image: url(/images/bg-curve-desktop.svg);
    background-repeat: no-repeat;
    background-size: contain;

}
.page1{

    width: 95%; 
    display: flex;
    justify-content:center;
   
    align-items: center;
    margin: 3%;
    padding-bottom: 15%; 
    /* padding-left: 4%; */
    /* padding-top: 8%; */
  
}

.page1-inner{
    width: 50%;
}
.page1-img1{
    width: 50%;
    text-align: center;
}
.page1-img1 img{
    width: 80%;
}


.page1-inner h1 {
    width: 87%;
    line-height: 40px;
}

.page1-inner p {
    width: 88%;
    line-height: 30px;
}
.page1-inner form{
    display: flex;
   
    gap: 20px;
}

.page1-inner input{
    width: fit-content;
    padding: 2% 6%;
}
.page1-inner button{
    width: fit-content;
    padding: 2% 7%;
    background-color: hsl(224, 93%, 58%);
    color: white;
    font-weight: bold;
}

.home2{

    width:100% ;
    background-image: url(/images/bg-curve-desktop.svg);
    background-repeat: no-repeat;
    background-size: contain;

}
.page2{
   
    width: 95%; 
    display: flex;
    justify-content:center;
   
    align-items: center;
    margin: 3%;
    padding-bottom: 8%; 
    /* padding-left: 4%; */
    /* padding-top: 8%; */
  
}

.page2-inner{
    width: 50%;
}
.page2-img1{
    width: 50%;
    text-align: center;
    margin-bottom: 4%;

}
.page2-img1 img{
    width: 80%;
    margin-bottom: 4%;

}
.page2-inner h1 {
   
    margin-bottom: 6%;

}
.page2-inner p {
    width: 86%;
    margin-bottom: 4%;

}

.page2-inner span{
   color:hsl(170, 45%, 43%);
   text-decoration-line:underline;
}

.page2-middle{
    padding-left: 4%;
    box-sizing: border-box;
    width: 70%;
    height: fit-content;
    background-color: white;
    border: none;
    cursor: pointer;
    box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
    margin-bottom: 3%;
}
.page2-author{
    display: flex;
    gap: 5px;
    justify-content: space-around;
    align-items: center;
   
    width: 80%;
    height: 10%;
}
.page2-middle p {
    width: 90%;
}
.page2-author1 img{
    width: 80%;
    object-fit: cover;
    border-radius:50%;
}
.page2-author2 {
    width: 100%;
   
}
.footer{
    display: flex;
    flex-direction: column;
    justify-content: center;
  
}

.footer-nav1{
    display: flex;
     align-items: center;
    justify-content: space-evenly;
    gap: 0px;
   
    
    color: white;
    background-color:  hsla(240, 22%, 44%, 0.89);
   
}
.footer-nav1-1{
    width: 50%;
    margin:5%;
}

.footer-nav1-1 p {
    width: 85%;
}

.footer-nav1-2 form{
    display: flex;
    flex-direction:column ;
    gap:20px ;
}
.footer-nav1-2 {
    width: 50%;
    margin:5%;
    
}
.footer-nav1-2 input {
    width: fit-content;
    padding: 2% 20%;
}

.footer-nav1-2 button {
    width: fit-content;
    padding: 2% 7%;
    background-color: hsl(224, 93%, 58%);
    color: white;
    font-weight: bold;
}
.footer-nav2{
    display: flex;
    align-items: center;
   justify-content: space-evenly;
 
   gap: 20px;
  
  
   color: white;
   background-color:  hsl(243, 87%, 12%);
  
}
.footer-nav2 a{
    text-decoration: none;
    color: white;
}
.footer-nav2-1{
    display: flex;
    flex-direction: column;
    gap: 10px;
    width: 29%;
    margin:9%;  
}
.footer-nav2-2{
    display: flex;
    flex-direction: column;
    gap: 10px;
    width: 25%;
    margin:3%;
}
.footer-nav2-3{
    display: flex;
    flex-direction: column;
    gap: 10px;
    width: 25%;
    margin:3%;
    padding-bottom: 3%;
}
.footer-nav2-4{
    display: flex;
    gap: 10px;
   
    width: 22%;
    margin:3%;
    padding-bottom: 7%;
    
}
.footer-nav2-4 i{
    border: 1px solid white;
    padding: 4px;
    border-radius: 50%;
}

.footer-nav2 a:hover{
    color: aqua;
}


button:hover{
    background-color: white;
    color: black;
    cursor: pointer;
}

@media(max-width:768px){
    body{
        width: 768px;
    }
    .main{
        width: 80%;
        display: flex;
        
        align-items: center;
        justify-content: center;
    }
    
    .navbar{
        
        display: flex;
        
        justify-content: space-between;
        align-items:center ;
        width: 60%;
       
        height: 150px;
        
    }
    
    .navbar ul{
        display: flex;
           gap: 20px;
    }
    
    ul a{
        text-decoration: none;
        color:hsla(0, 2%, 10%, 0.664);
        font-weight: 400;
    
    }

    .page1{
    
        width: 75%; 

        justify-content:center;
        flex-direction: column-reverse;
    }
    
    .page1-inner{
        width: 80%;
        text-align: center;
    }
    .page1-img1{
        width: 100%;
        text-align: center;
    }
    .page1-img1 img{
        width: 80%;
    }
    
    
    .page1-inner h1 {
        width: 87%;
        line-height: 40px;
    }
    
    .page1-inner p {
        width: 88%;
        line-height: 30px;
        margin-bottom: 5%;
    }
    .page1-inner form{
       
        flex-direction: column;
        justify-content: center;
        align-items: center;
       
    }
    .page2{
       
        width: 95%; 
        flex-direction: column-reverse;
       
    }
    
    .page2-inner{
        width: 100%;
        text-align: center;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .page2-img1{
        width: 100%;
        text-align: center;
        margin-bottom: 4%;
    
    }
    .page2-img1 img{
        width: 80%;
        margin-bottom: 4%;
    
    }
    .page2-inner h1 {
       
        margin-bottom: 6%;
    
    }
    .page2-inner p {
    
        width: 70%;
        margin-bottom: 3%;
    
    }

    
    .page2-middle{
        padding-left: 4%;
        box-sizing: border-box;
        width: 70%;
        height: fit-content;
        background-color: white;
        border: none;
        cursor: pointer;
        box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
        margin-bottom: 3%;
        text-align: justify;
    }
    .page2-author{
        display: flex;
        gap: 5px;
        justify-content: space-around;
        align-items:center;
        flex-wrap: nowrap;
        width: 80%;
        height: 10%;
    }
    .page2-middle p {
        width: 90%;
    }
    .page2-author1 img{
        width: 80%;
        object-fit: cover;
        border-radius:50%;
    }
    .page2-author2 {
       margin-bottom: 5%;
        width: 100%;
       
    }
    .footer{
        display: flex;
        flex-direction: column;
        justify-content: center;

    }
    
    .footer-nav1{
       flex-direction: column;
    }
    .footer-nav1-1{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        width: 90%;
        margin:5%;
        text-align: center;
    }
    
    .footer-nav1-1 p {

        width: 70%;
    }
    
    .footer-nav1-2 form{
        display: flex;
        flex-direction:column ;
        justify-content: center;
        align-items: center;
        gap:20px ;
    }
    .footer-nav1-2 {
        width: 50%;
        
    }
    .footer-nav1-2 input {
        width: fit-content;
        padding: 2% 20%;
    }
    
    .footer-nav1-2 button {
        width: fit-content;
        padding: 2% 7%;
        background-color: hsl(224, 93%, 58%);
        color: white;
        font-weight: bold;
    }
    .footer-nav2{
        display: flex;
        flex-direction:row;
        flex-wrap: wrap;
        align-items: center;
       justify-content: space-evenly;
       
       gap: 20px;
      
      
       color: white;
       background-color:  hsl(243, 87%, 12%);
      
    }
    .footer-nav2 a{
        text-decoration: none;
        color: white;
    }
    .footer-nav2-1{
        display: flex;
        flex-direction: column;
        
        gap: 10px;
        width: 30%;
        margin:7%;  
    }
    .footer-nav2-2{
        display: flex;
        flex-direction: column;
        gap: 10px;
        width: 30%;
        margin:7%;
    }
    .footer-nav2-3{
        display: flex;
        flex-direction: column;
        gap: 10px;
        width: 30%;
        margin:8%;
        padding-bottom: 3%;
    }
    .footer-nav2-4{
        display: flex;
        gap: 10px;
        
        width: 30%;
        min-width: 100px;
        margin:7%;
        padding-bottom: 9%;
        
    }
    .footer-nav2-4 i{
        border: 1px solid white;
        padding: 4px;
        border-radius: 50%;
    }
    
    .footer-nav2 a:hover{
        color: aqua;
    }
    
    
    button:hover{
        background-color: white;
        color: black;
        cursor: pointer;
    }
    
   
   
}
---------------------------------------------
  body{
        width: 768px;
    }
    .main{
        width: 80%;
        display: flex;
        
        align-items: center;
        justify-content: center;
    }
    
    .navbar{
        
        display: flex;
        
        justify-content: space-between;
        align-items:center ;
        width: 60%;
       
        height: 150px;
        
    }
    
    .navbar ul{
        display: flex;
           gap: 20px;
    }
    
    ul a{
        text-decoration: none;
        color:hsla(0, 2%, 10%, 0.664);
        font-weight: 400;
    
    }

    .page1{
    
        width: 75%; 

        justify-content:center;
        flex-direction: column-reverse;
    }
    
    .page1-inner{
        width: 80%;
        text-align: center;
    }
    .page1-img1{
        width: 100%;
        text-align: center;
    }
    .page1-img1 img{
        width: 80%;
    }
    
    
    .page1-inner h1 {
        width: 87%;
        line-height: 40px;
    }
    
    .page1-inner p {
        width: 88%;
        line-height: 30px;
        margin-bottom: 5%;
    }
    .page1-inner form{
       
        flex-direction: column;
        justify-content: center;
        align-items: center;
       
    }
    .page2{
       
        width: 95%; 
        flex-direction: column-reverse;
       
    }
    
    .page2-inner{
        width: 100%;
        text-align: center;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .page2-img1{
        width: 100%;
        text-align: center;
        margin-bottom: 4%;
    
    }
    .page2-img1 img{
        width: 80%;
        margin-bottom: 4%;
    
    }
    .page2-inner h1 {
       
        margin-bottom: 6%;
    
    }
    .page2-inner p {
    
        width: 70%;
        margin-bottom: 3%;
    
    }

    
    .page2-middle{
        padding-left: 4%;
        box-sizing: border-box;
        width: 70%;
        height: fit-content;
        background-color: white;
        border: none;
        cursor: pointer;
        box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
        margin-bottom: 3%;
        text-align: justify;
    }
    .page2-author{
        display: flex;
        gap: 5px;
        justify-content: space-around;
        align-items:center;
        flex-wrap: nowrap;
        width: 80%;
        height: 10%;
    }
    .page2-middle p {
        width: 90%;
    }
    .page2-author1 img{
        width: 80%;
        object-fit: cover;
        border-radius:50%;
    }
    .page2-author2 {
       margin-bottom: 5%;
        width: 100%;
       
    }
    .footer{
        display: flex;
        flex-direction: column;
        justify-content: center;

    }
    
    .footer-nav1{
       flex-direction: column;
    }
    .footer-nav1-1{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        width: 90%;
        margin:5%;
        text-align: center;
    }
    
    .footer-nav1-1 p {

        width: 70%;
    }
    
    .footer-nav1-2 form{
        display: flex;
        flex-direction:column ;
        justify-content: center;
        align-items: center;
        gap:20px ;
    }
    .footer-nav1-2 {
        width: 50%;
        
    }
    .footer-nav1-2 input {
        width: fit-content;
        padding: 2% 20%;
    }
    
    .footer-nav1-2 button {
        width: fit-content;
        padding: 2% 7%;
        background-color: hsl(224, 93%, 58%);
        color: white;
        font-weight: bold;
    }
    .footer-nav2{
        display: flex;
        flex-direction:row;
        flex-wrap: wrap;
        align-items: center;
       justify-content: space-evenly;
       
       gap: 20px;
      
      
       color: white;
       background-color:  hsl(243, 87%, 12%);
      
    }
    .footer-nav2 a{
        text-decoration: none;
        color: white;
    }
    .footer-nav2-1{
        display: flex;
        flex-direction: column;
        
        gap: 10px;
        width: 30%;
        margin:7%;  
    }
    .footer-nav2-2{
        display: flex;
        flex-direction: column;
        gap: 10px;
        width: 30%;
        margin:7%;
    }
    .footer-nav2-3{
        display: flex;
        flex-direction: column;
        gap: 10px;
        width: 30%;
        margin:8%;
        padding-bottom: 3%;
    }
    .footer-nav2-4{
        display: flex;
        gap: 10px;
        
        width: 30%;
        min-width: 100px;
        margin:7%;
        padding-bottom: 9%;
        
    }
    .footer-nav2-4 i{
        border: 1px solid white;
        padding: 4px;
        border-radius: 50%;
    }
    
    .footer-nav2 a:hover{
        color: aqua;
    }
    
    
    button:hover{
        background-color: white;
        color: black;
        cursor: pointer;
    }
    
   
   
}
