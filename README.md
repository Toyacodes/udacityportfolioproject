# udacityportfolioproject
Personal Portfolio Project


<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Nails, Nails, and More Nails!</title>
    <meta
      content="width=device-width, initial-scale=1, maximum-scale=1"
      name="viewport"
    />
    
    <link rel="stylesheet" href="style.css">

  </head>

  <body>
    <main>
       
  <div class = "container">
   
    <div class="header box"><strong>GEMINI NAILZ</strong><br><em>Where we discuss all things Nails!</em>
      
       <img src="screenshot.png" alt="Head Shot" width="100" height="100">
    </div>
   
    <div class="sidebar box">
  
      <h3><u>Getting Your Nails Done: The Ultimate Act Of Self-Care</u>.</h3>
      <p> Getting your nails done isn't just a beauty<br> treatment- it's an act of self care. The <br> process of getting your nails done creates a moment of relaxation and indulgence,<br> and the end result can brighten your mood<br> and give you a confidence boost. Whether it's<br> a stylish manicure or an intricate nail design,<br> the experience of getting your nails done can<br> bring you joy and help you express your personal style. </p>
      <ul>
        <li>Relaxed</li>
        <li>Pampered</li>
        <li>Confident</li>
        <li>Creative</li>
      </ul><hr>
      <h3><u>Treatments Available</u></h3>
      <p> From a classic French Manicure to an intricate nail design, the spectrum of nail treatments is diverse, offering something for everyone's style and taste. Eplore the difference types of nail treatments available and find your perfect match.
      <ul>
        <li><i><strong><u>Classic Manicures-</u></i></strong> Involves trimming, filing and buffing the nails and cuticles, follwed by a hand massage and nail polish application.</li>
        <li><i><strong><u>Gel Manicures</u></i></strong>- Uses a special gel polish that is cured with a UV light, creating a longer-lasting and more durable manicure than a classic manicure.</li>
        <li><i><strong><u>Nail Extensions</u></i></strong>- Use glue, gel or acrylic to lengthen the nail, allowing for a greater freedom of expression and the opportunity to experiment with nail art.</li>  
      </ul>
       <h1><u>Follow Me To Find Out More!</u></h1>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="https://www.instagram.com/_gemini_nailz?igshid=ZDdkNTZiNTM=/">Contact</a>
      </div> 
    
  
  <div class="content box">
   
    <h3><u>About me</u></h3>
    <p>I am a Nail Technician with over 6 years of experience in the beauty industry.<br> I have a passion for creating beautiful and unique nail designs that make my clients feel confident and stylish.<br> Over the years, I have honed my skills in various nail techniques, such as acrylics, gels, and nail art.<br> I am decicated to providing my clients with the highest quality service, using only the best products and tools.<br> With my expertise and attention to detail, I am committed to ensuring <br>that each client leaves feeling satisfied and delighted with their new set of nails.</p>
  <div class="iframe-container">  
<iframe width="800" height="350" src="https://www.youtube.com/embed/ERRwsWVgsko" title="nails, nails, nails!!!" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
    
    
  
      
     <article> 
      
       <h3><u>The Self-Care Aspect of Nail Treatments</u></h3>
       <p> Getting your nails done isn't just about looking good- it's about<br> feeling good too. The act of getting your nails done is an opportunity to<br> treat yourself to a moment of relaxation and self-care.<br> By investing in your nails, you're investing in yourself.</p><br>
       <h4><u> How It Can Brighten Your Mood</u></h4>
       <p>The process of getting your nails done is a moment of indulgence and <br>relaxtion that can brighten your mood and help you feel<br> rejuvenated. With regular nail appointments, you can stay on <br>top of you self-care routine and maintain a positive outlook on life.</p>
       
      </article>
      </div>
    </div>
    </div>
     <!------->
    
    <div class="footer box">@ JST, LLC. - Toya M.</div>
    
  </div>
    </main>
  </body>
</html>

@import "screenshot.png";
@import url(C:\Users\User\portfolio.html\screenshot.png);







.container{
    
    display: grid;
    grid-template-columns: 300px 300px 300px;
    grid-template-rows: 250px 900px;
    grid-template-areas: 
    "hd hd hd hd hd hd hd hd"
    "sd main main main main main main main"
    "ft ft ft ft ft ft ft ft";
    border: 1px solid black;

}

* {
box-sizing: relative;
}

@media (min-width: 600px) and (max-width:900px) {

}

@media (min-width:901px) {

}
/*
@media only screen and (min-width: 300px) {
/* For mobile phones: 
.menu, .main, .right {
  width:100%;
  flex-wrap: 100%;
}
}
*/



<!---- CSS below---->


.box{
/* width: 250px;
  height: 100%; */
  border: 2px solid black;
  background: #F8FA9D;

}

img{
border-radius: 10px;
 border: 3px solid black;
 margin-left: 150px;
margin-right: 20px;
}






.header{

  text-shadow: 1px 1px 2px green, 0 0 30px red, 0 0 50px gold;
  background-color: lightblue;
  grid-area:hd;
  font-size: 100px;
  background-image: linear-gradient(to right, red,orange,yellow,green,blue,indigo,violet);
  text-align: center;
  padding-top: 1%;
  padding-left: 10px;
}

em{
font-size: 50px;

text-align: center;
}





h3{
font-size: 20px;
text-align:center;
}


.iframe-container{
display: relative;
align-content: center;
margin-left: 250px;
}




.footer{
    width: 1350px;
  grid-area: ft; 
  background-color: green;
 font-weight: white;
font-size: 10px;
}
.sidebar{
  grid-area: sd;
 /* background-color: yellow ;*/
background-image: linear-gradient(to right, red,orange,yellow,green,blue,indigo,violet);
 text-shadow: 1px 1px 2px green, 0 0 30px red, 0 0 50px gold; 
 
}

h1{
font-size: 20px;
}
h2{
font-size: 20px;
text-align: center;
font-size: 50px;
padding-top: auto;
padding-bottom: auto-flow
}

p {
text-align: center;
color: black;
font-size: 15px;
}

h4{
text-align: center;
}

.content{
  grid-area: main;
 /* background-color: yellow;*/
  background-image: linear-gradient(to right, red,orange,yellow,green,blue,indigo,violet);
  
}

.content p {
text-align: center;
font-family: cursive ;
font-weight: bolder;
font-size: 15px;

}










