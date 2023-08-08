<html lang="en-gb">
  
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Welcome to my Page </title>
    <!-- reset.css taken from other sessions, applied first to ensure systle is applied correctly -->
  <link rel="stylesheet" href="./assets/css/style.css" />
  <link rel="stylesheet" href="./assets/css/style.css" />
</head>

<body>
  <!-- main logo / nav -->
  <header>
    <h1>Fabiola Djikigoue // Portfolio Project</h1>
    <nav>
      <a class="bannerlink" href="">About Me</a> 
      <a class="bannerlink" href="">My Projects</a> 
      <a class="bannerlink" href="">Contact Me</a> 
    </nav>
   <header>

  <!-- hero banner -->
  <section class="hero-banner">
    <div>
      <h2>Cool subtitle here!</h2>
      <img src="../starter/images/02-hero-bg.jpg" alt="">
    </div>
  </section>

  <main class="mainContent">
    <!--  about me  -->
    <section class="page-section" id="about">
      <h2>About me </h2>
      <p>Some stuff about me :)</p>
      <img src="" alt="Image to do with me">
    </section>

    <!-- portfolio container -->
    </a><section class="page-section flexGrid" id="work"
      <h2>Projects</h2>
      <!--list of project displayed here-->
     <ul>
       <li id="projecthighligh"><a href="https://github.com/therandomer/Final-FYP"> bullets in Space!</a>
       <p>Highligh Project Brief</p>
       <img src="../starter/images/02-hero-bg.jpg" alt=" Highlight Project Image"></li>
    
        <li id="project"><a href="">Project 1 (TBD)</a>
        <p>Project 1 Brief</p>
        <img src="../starter/images/02-portfolio-1.jpg" alt="Project 1 Pic"></li>
     </ul>
     <ul>
        <li id="project"><a href="">Project 2 (TBD)</a>
        <p>Project 2 Brief</p>
        <img src="../starter/images/02-portfolio-2.jpg" alt="Project 2 Pic"></li>
        </ul>
      <ul>
        <li id="project"><a href="">Project 3 (TBD)</a>
        <p>Project 3 Brief</p>
        <img src="../starter/images/02-portfolio-3.jpg" alt="Project 3 Pic"></li>
       </ul>
       <ul>
         <li id="project"><a href="">Project 4 (TBD)</a>
          <p>Project 4 Brief</p>
          <img src="../starter/images/02-portfolio-4.jpg" alt= Project 4 Pic"></li>
      



    </li></ul></section>

    <!-- contact -->
    <section class="page-section contact" id="contact">
      <h2>Contact Me</h2>
      <img src="" alt="phone Icone">
      <!-- Can add whatever phone number here -->
      <a href="tel: 077493674993"> phone me!</a>
      <!-- will mail selected email address -->
      <img src="../starter/images/emial.png" alt="email Icone">
      <a href="email:fabioladjikigoue@hotmail.co.uk"> email me!</a>
    </section
  </main>

  
</body></html>

:root{
    --navBarTextColour: white;
    --navBarBackgroundColour: rgb(38, 38, 132);
    --baseDisplay: flex;
  }
  
  * {
    box-sizing: border-box;
  }
  
  /*!Remove this*/
  img {
    width: 40%;
 
  }
  
  body {
    margin: 0%;
    padding: 0;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    line-height: 1.5;


  }
  
  h1 {
    font-size: var(--headerfontsize);
    margin-bottom: var(--smallBottomMargin);
  }

  h2 {
    font-size: var(--headerfontsize) - var(--smallHeaderOffset);
    margin-bottom: var(--smallBottomMargin);
  }

  header {
    padding: 40px;
    text-align: center;
    background: white(0, 0, 0);
    color: var(--headingColour); 
  }
 
nav {
    display: var(--baseDisplay);
    background-color: beige;
}

nav {
    color: black;
    padding: 14px 20px;
    text-decoration: none;
    text-align: center;
}


  h3,
  h4,
  h5,
  h6 {
    margin: 0;
  }
  
  p {
    margin: 0;
  }

  .flexGrid{
    display: flex;
    justify-content: flex-start;
    flex-direction: row;
    flex-wrap: wrap-reverse;
  }

  .flexGrid a{ 
    font-size: flex;
    text-decoration: rgb(0, 0, 0);
    text-align: center;
  }

  .flexGrid iframe{
    border-radius: 50%;
    rotate: deg(20);
    border-color: rgb(94, 66, 25);
  }
  .pageSection{
    display: flex;
  }
  /*Media query for mobile device.*/ 
  @media only screen and (max-width: 600px)
  {

 .flexGrid{
     display: block;
     margin: auto;
     cursor: zoom-in;
     background-color: hsl(0, 0%, 90%);
     transition: background-color 300ms;
    }
   }

 .flexGrid {
     display: block;
     margin: auto;
     cursor: zoom-in;
     background-color: hsl(0, 0%, 90%);
     transition: background-color 300ms;
    }

