# webpage
This a simple webpage for practice
<!DOCTYPE html> 
 <html lang="en"> 
  
 <head> 
   <meta charset="UTF-8"> 
   <meta http-equiv="X-UA-Compatible" content="IE=Edge"> 
   <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
   <script src="https://kit.fontawesome.com/f743fcc815.js" crossorigin="anonymous"></script> 
   <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Tangerine|DM Serif Display|Pacifico|Raleway|Lora&effect=emboss"> 
   <title>SweetChef Organic Restaurant</title> 
  
   <!-- HTML --> 
  
  
   <!-- Custom Styles --> 
   <link rel="stylesheet" href="style.css"> 
 </head> 
  
 <body> 
   <div id="nav" class="sidenav"> 
     <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a> 
     <a href="home.asp">Home</a> 
   </div> 
   <div id="banner"> 
     <div id="navbar"> 
       <i class="fa-solid fa-bars fa-lg" onclick=openNav()></i> 
     </div> 
     <img src="logo.png" alt="logo" class="logo"> 
     <p class="motto">One Step to Making a Good Start</p> 
     <p class="info">Mauris fermentum tortor non enim aliquet condimentum. Nam aliquam pretium feugiat. Duis sem est, viverra eu interdum ac, suscipit nec mauris. Suspendisse commodo tempor sagittis! In justo est, sollicitudin eu scelerisque pretium, placerat eget elit.</p> 
     <div id="arrow"> 
       <i class='fas fa-play'></i> 
     </div> 
   </div> 
   <div id="menu"> 
     <div> 
       <p class="price">OUR MENU</p> 
       <p class="motto2">Delicious From The Chef</p> 
     </div> 
     <div> 
       <p class="price">PEAR SALAD / $11</p> 
       <p class="food">Reid’s Orchard Pears / Bitter Greens / Granola / Big Firefly / Farms Black and Blue / Pine Nut Vinaigrette</p> 
  
       <p class="price">BRODETTO DI PESCE / $9</p> 
       <p class="food">Adriatic Seafood Soup / Clams / Prawns / Livornese / Langoustine Scallop / Celery / Olive</p> 
  
       <p class="price">FARM GREENS / $9</p> 
       <p class="food">Honey Vinaigrette / House Cheese Crouton / Fine Herbs</p> 
  
       <p class="price">GRILLED KALE / $9</p> 
       <p class="food">Bitter Greens / House Cheese Crouton / Kamon Iberico</p> 
  
       <p class="price">RICOTTA GNUD / $18</p> 
       <p class="food">Marinated Sardine / Red Currant / Chanterelles / Pine Nuts / Mantecato Vitello / Fennel / Olive / Pepitas</p> 
  
       <p class="price">CANESTRELLI / $18</p> 
       <p class="food">Reid Orchatd Pears / Bitter Greens / House Cheese Crouton / Marinated Sardine / Chanterelles / Clams</p> 
     </div> 
  
     <div id="sweets"> 
       <div class="it"> 
         <img src="icecream.png" alt=""> <br> <span class="deets">TOP ICE-CREAM </span> 
       </div> 
       <div class="it"> 
         <img src="sorbet.png" alt=""><br><span class="deets">FRUIT SORBETS</span> 
       </div> 
       <div class="it"> 
         <img src="cake.png" alt=""><br><span class="deets">DESSERTS</span> 
       </div> 
       <div class="it"> 
         <img src="sundae.png" alt=""><br><span class="deets">SUNDAES</span> 
       </div> 
       <div class="it"> 
         <img src="smoothie.png" alt=""><br><span class="deets">SMOOTHIES</span> 
       </div> 
       <div class="it"> 
         <img src="cocktail.png" alt=""><br><span class="deets">DRINKS & MORE</span> 
       </div> 
     </div> 
  
     <div id="about"> 
       <div id="about1"><img src="chocolatecake.jpg" alt=""></div> 
       <div id="about2" class="history"> 
         <span class="header">HISTORY</span> 
         <span class="headline">Strange story of the emergence of healthy food</span> 
         <span class="text">Sample text. Click to select the text box. Click again or double click to start editing the text.</span> 
         <span class="readmore"><a href="history.asp">READ MORE</a></span> 
       </div> 
       <div id="about1"><img src="breakfast.jpg" alt=""></div> 
       <div id="about2"> 
         <span class="header">COMMUNITY</span> 
         <span class="headline">Healthy food in social networks, with us interesting</span> 
         <span class="text">Sample text. Click to select the text box. Click again or double click to start editing the text.</span> 
         <span class="readmore"><a href="community.asp">READ MORE</a></span> 
       </div> 
       <div id="about1" class="granola"><img src="granola.jpg" alt=""> 
       </div> 
       <div id="about2" class="philosophy"> 
         <span class="header">PHILOSOPHY</span> 
         <span class="headline">Only the best food, the best musicians the best guests</span> 
         <span class="text">Sample text. Click to select the text box. Click again or double click to start editing the text.</span> 
         <span class="readmore"><a href="philosophy.asp">READ MORE</a></span> 
       </div> 
     </div> 
  
     <section id="reviews"> 
       <div class="reviews_container"> 
         <div class="reviews_item"> 
           <div class="reviews_info" style="order: 1"> 
             <h3 class="health">Health is the most precious</h3> 
             <p class="reviews_deets">While it is important to have naturally occurring sugars in your diet, many foods contain harmful added sugars that contain no nutritional value.</p> 
             <p class="reviews_deets">According to a study conducted by the University of Florida, the brain releases heroin-like chemicals called endogenous opioids when an individual indulges on sweet, salty or fatty foods. </p> 
             <span class="readmore"><a href="#">READ MORE</a></span> 
           </div> 
           <img src="review1.jpeg" alt="" style="order: 3"> 
         </div> 
  
         <div class="reviews_item"> 
           <img src="review2.jpeg" alt="" style="order: 2"> 
           <div class="reviews_info" style="order: 4"> 
             <p class="price">BAKERY</p> 
             <h3 class="health">Reviews</h3> 
             <span class="reviews_img"><img src="quote.png" alt=""></span> 
             <p class="reviews_deets">We bring the season’s best mix of organic produce and hand-crafted farm products conveniently to your door by growing and partnering with local farms and artisans in your area.</p> 
             <span class="author"> 
               <p>– LOO HUDSON</p> 
             </span> 
           </div> 
         </div> 
       </div> 
     </section> 
  
     <section id="tutorial"> 
       <div> 
         <h4 class="tutorial_head">Learn Cooking Online</h4> 
         <p class="tutorial_text">Suspendisse commodo tempor sagittis! In justo est, sollicitudin eu scelerisque pretium, placerat eget elit.</p> 
       </div> 
       <div class="tutorial_container"> 
         <div class="slides fade"> 
           <div class="numbertext">1/6</div> 
           <img src="kitchen_cabinet.jpg" style="width: 100%" id="tutorial_img1"> 
         </div> 
         <div class="slides fade"> 
           <div class="numbertext">2/6</div> 
           <img src="cake_slice.jpg" style="width: 100%" id="tutorial_img2"> 
         </div> 
         <div class="slides fade"> 
           <div class="numbertext">3/6</div> 
           <img src="pancake_berry.jpg" style="width: 100%" id="tutorial_img3"> 
         </div> 
         <div class="slides fade"> 
           <div class="numbertext">4/6</div> 
           <img src="salad.jpeg" style="width: 100%; object-fit: cover;" id="tutorial_img4"> 
         </div> 
         <div class="slides fade"> 
           <div class="numbertext">5/6</div> 
           <img src="sponge_cake.jpg" style="width: 100%" id="tutorial_img5"> 
         </div> 
         <div class="slides fade"> 
           <div class="numbertext">6/6</div> 
           <img src="breakfast_table.jpg" style="width: 100%" id="tutorial_img6"> 
         </div> 
         <a class="prev" onclick="plusSlides(-1)">&#10094;</a> 
         <a class="next" onclick="plusSlides(1)">&#10095;</a> 
       </div> 
       <br> 
       <div style="text-align:center"> 
         <span class="dot" onclick="currentSlide(1)"></span> 
         <span class="dot" onclick="currentSlide(2)"></span> 
         <span class="dot" onclick="currentSlide(3)"></span> 
         <span class="dot" onclick="currentSlide(4)"></span> 
         <span class="dot" onclick="currentSlide(5)"></span> 
         <span class="dot" onclick="currentSlide(6)"></span> 
       </div> 
       <div id="myModal" class="modal"> 
         <span class="close">&times;</span> 
         <img class="modal-content" id="img01"> 
       </div> 
       <span class="readmore_tutorials"> 
         <a href="#">READ MORE</a> 
       </span> 
     </section> 
  
     <section id="pictures"> 
       <div class="pictures_container"> 
         <div class="pictures_item"> 
           <img src="stepone.jpeg" alt=""> 
         </div> 
         <div class="pictures_item"> 
           <img src="steptwo.jpeg" alt=""> 
         </div> 
         <div class="pictures_item"> 
           <img src="stepthree.jpeg" alt=""> 
         </div> 
       </div> 
     </section> 
  
     <section id="conclusion"> 
       <div> 
         <p class="conclusion">We bring the season’s best mix of organic produce and hand-crafted farm products conveniently to your door by growing and partnering with local farms and artisans in your area.</p> 
         <div class="socials" style="color: white"> 
           <a href=""><i class="fa-brands fa-facebook-f"></i></a> 
           <a href="https://twitter.com/Moyo_61?t=X8YxoltIwea6ssk0JWfALg&s=09" target="_blank"><i class="fa-brands fa-twitter"></i></a> 
           <a href=""><i class="fa-brands fa-instagram"></i></a> 
         </div> 
       </div> 
     </section> 
      
     <footer> 
       <div> 
         <p><span>©</span> Code by MoyoSharon</p> 
       </div> 
       <div> 
         <a href="https://github.com/MoyoSharon/sweetchef" target="_blank">Link To Github Repo</a> 
       </div> 
     </footer> 
     <script src="main.js"></script> 
 </body> 
  
 </html>
