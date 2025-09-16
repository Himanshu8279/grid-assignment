# grid-assignment

Q=1 

<!DOCTYPE>
 <html>
    <head>

             <title>  question 1</title>

    </head>

<link rel="stylesheet" href="grid-assignment1.css">

  <body>
   
        <div class="main-div">


            <div class="image image-1">

              <img src="https://cdn.britannica.com/48/252748-050-C514EFDB/Virat-Kohli-India-celebrates-50th-century-Cricket-November-15-2023.jpg">     
           </div>
          

            <div class="image image-2">  

               <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTbA4lpIEQlOC1h-JvHyC50yoCOPDApQ9cYWq6h1Y5jxSjek7c3CKiMNWxW4bUB3Ln3e04&usqp=CAU">     
        
           </div>
          
           
            <div class="image image-3">  

                <img src="https://i.pinimg.com/736x/3d/b8/e2/3db8e2db9ba7b3ed66c214e0f44ff87e.jpg">
        
           </div>
          
           
                    

                <div class="image image-4">  

                     <img src="https://m.media-amazon.com/images/I/61CG8tD+GFL.jpg">
                         
                </div>
          
     


               <div class="image image-5">  

                    <img src="https://media.gettyimages.com/id/2186592795/photo/perth-australia-virat-kohli-of-india-celebrates-scoring-a-century-during-day-three-of-the.jpg?s=612x612&w=gi&k=20&c=X-KlrGevMjbt0mqtmVvIZ4QZw2H1GwYz0kRX8sFiY_4=">

                     
              </div>
         
            
           


               <div class="image image-6">  

                    <img src="https://m.media-amazon.com/images/I/51Jeu+ot7EL._UF1000,1000_QL80_.jpg">

                      
              </div>

                  

           
              






        </div>

  </body>



  style= 

  .main-div{


display: grid;
width: 650px;

border: solid black 2px;
grid-template-columns: 200px 200px 200px;
grid-template-rows: 100px 100px 100px;

 
gap: 5px;
background-color: white;
padding: 10px;

grid-template-areas :

"image-1 image-1 image-2"
"image-3 image-4 image-6"
"image-3 image-5 image-6";




}
img{

height: 100%;
width: 100%;
border-radius:5px;



}

.image-1{

grid-area: image-1;

}

.image-2{

grid-area: image-2;

}

.image-3{

grid-area: image-3;

}

.image-4{

grid-area: image-4;

}

.image-5{

grid-area: image-5;

}

.image-6{

grid-area: image-6;

}



Q=2 


<!DOCTYPE>
 <html>
    <head>

             <title>  question 1</title>

    </head>

<link rel="stylesheet" href="grid-assignment2.css">

  <body>
   
        <div class="main-div">


           <div class="box box-1">A</div>
           <div class="box box-2">b</div>
           <div class="box box-3">c</div>
           <div class="box box-4">d</div>
             
                  

           
       </div>

  </body>

<html/>


stylesheet  =


.main-div{

display: grid;
width: 700px;


grid-template-columns: 200px 200px 200px;
grid-template-rows: 100px 100px;
border: solid  black 2px;

grid-template-areas :

"box-1 box-1 box-2"
"box-3 box-4 box-2";

gap: 10px;
padding: 10px;



}
.box{

border: solid white 2px;
text-align: center;
font-wight: bold;
font-size: 4rem;
border-radius: 10px;
}

.box-1{

grid-area: box-1;
background-color: yellow;
}

.box-2{

grid-area: box-2;
background-color: yellow;
}

.box-3{

grid-area: box-3;
background-color: yellow;
}

.box-4{

grid-area: box-4;
background-color: yellow;
}


<html/>
