

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <script
      src="https://kit.fontawesome.com/0ede200358.js"
      crossorigin="anonymous"
    ></script>
    <title>My portfoilo</title>
  </head>
  <body>
    <style>:root {
      --main-color:gold ;
      --secondary-color:black;
      --tetiary-color: magenta;
      --gray-color: cyan;
      --secondgray-color: black;
    }
    
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    
    .links a {
      width: 150px;
      height: 50px;
      border: 1px solid #ffffff;
      padding: 5px 15px;
      margin-top: 10px;
      text-decoration: none;
      color: var(--secondary-color);
      margin-right: 10px;
    }
    .cv {
      background-color: var(--tetiary-color);
      border: 1px solid var(--tetiary-color) !important;
    }
    body {
      background: var(--main-color);
      color: var(--secondary-color);
      font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
      padding: 20px 50px;
    }
    
    /* header sections */
    
    header {
      /* width: 100vw; */
      height: 65px;
      /* padding: 20px 40px 10px 40px; */
    }
   
    .nav {
      width: 100%;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    .nav > .logo {
      font-size: 28px;
      font: bolder;
      font-weight: 700;
    }
    .nav > .el > ul {
      display: flex;
      flex-direction: row;
      list-style-type: none;
      gap: 20px;
    }
    main {
      margin-bottom: 200px;
    }
    /* hero section */
    .hero {
      height: 500px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    
    .intro {
      width: 45%;
      height: 100%;
      display: inherit;
      justify-content: center;
      align-items: center;
      flex-direction: column;
    }
    .intro h1 {
      font-size: 50px;
    }
    .intro p {
      color: var(--secondgray-color);
      margin-bottom: 20px;
    }
    .image {
      width: 45%;
      height: 100%;
      border-radius: 50%;
      background-color: #202020;
      display: flex;
      justify-content: center;
      align-items: center;
      border: 1px solid magenta;
    }
    .image > img {
      width: 95%;
      height: 95%;
      border-radius: 50%;
    }
    
    /* About Section */
    .about,
    .services {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      margin-top: 50px;
    }
    .about .title,
    .services .title,
    .forms .title {
      font-size: 35px;
      font-weight: 800;
      padding-bottom: 20px;
    }
    .about .para {
      width: 60%;
      text-align: center;
      padding-bottom: 50px;
    }
    
    .about .socails,
    .services .wcards,
    .services .skillcard {
      width: 100%;
      display: flex;
      justify-content: space-between;
    }
    .about .socails .card {
      display: inherit;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      gap: 5px;
      width: 20%;
      height: 150px;
    }
    
    .about .circ {
      width: 50px;
      height: 50px;
      border-radius: 50%;
      background-color: var(--gray-color);
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .about .circ > div {
      width: 10px;
      height: 10px;
      border-radius: 50%;
      background-color: var(--tetiary-color);
    }
    .wcards {
      justify-content: center !important;
      gap: 50px;
      padding-bottom: 50px;
      padding-top: 50px;
    }
    .wcards .card {
      width: 35%;
      background-color: var(--gray-color);
      font-size: 30px;
      padding: 40px;
      padding-right: 150px;
    }
    .wcards .card > .icon {
      color: var(--tetiary-color);
      font-size: 50px;
    }
    .wcards .card:nth-child(1) {
      border-bottom: 3px solid var(--tetiary-color);
    }
    .wcards .card:hover {
      border-bottom: 3px solid var(--tetiary-color);
    }
    
    .skillcard {
      justify-content: center !important;
      background-color: var(--gray-color);
      padding: 40px 20px;
      padding-left: 100px;
      margin-top: 30px;
    }
    .skillcard > .card {
      width: 20%;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    
    .skillcard > .card > .per {
      font-size: 50px;
      font-weight: 900;
      color: var(--secondgray-color);
    }
    
    .skillcard > .card > .name {
      text-transform: uppercase;
      color: var(--tetiary-color);
    }
    .forms {
      width: 100%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      margin-top: 50px;
    }
    form {
      width: 50%;
      align-self: center;
      margin-top: 50px;
    
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      gap: 20px;
    }
    form > input {
      border: none;
      background: transparent;
      width: 48%;
      height: 40px;
      border-bottom: 1px solid #c4c4c4;
      outline: none;
      font-size: 16px;
    }
    form > textarea {
      border: none;
      background: transparent;
    
      border: 1px solid #c4c4c4;
      outline: none;
      font-size: 16px;
    }
    
    form > a {
      width: 150px;
      height: 50px;
      border: 1px solid #ffffff;
      padding: 5px 15px;
      margin-top: 10px;
      text-decoration: none;
      color: var(--secondary-color);
      margin-right: 10px;
      display: flex;
      justify-content: center;
      align-items: center;
      margin: auto;
    }
    
    /* footer */
    footer {
      display: flex;
      font-size: 14px;
      justify-content: center;
      align-items: center;
      color: var(--secondgray-color);
    }
    </style>
    <!-- header start -->
    <header class="header">
      <nav class="nav">
        <div class="logo">JORAM MUSAU</div>
        <div class="el">
          <ul class="list">
            <li class="list-items">About me</li>
            <li class="list-items">Contact me</li>
            <li class="list-items">Services</li>
          </ul>
        </div>
      </nav>
    </header>
    <!-- HEader End -->

    <!-- Main Start -->
    <main class="main">
      <!-- Hero Section Start -->
      <section class="hero" id="hero">
        <div class="intro">
          <h1>
            Hi I am <br />
            Joram Musau
          </h1>
          <p>Frontend Developer</p>
          <div class="links">
            <a href="#" class="cv">Download cv</a>
            <a href="#">Learn more</a>
          </div>
        </div>
        <div class="image">
          <img src="c:\Users\Student-510A2C\Pictures\New folder\Polish_20240204_205445239.jpg" alt="image of me" />
        </div>
      </section>
      <section class="about" id="About">
        <h2 class="title">About</h2>
        <div class="para;text-color:red">


         My name is Joram Musau. I am a computer scientist and a software Developer based in Kenya. Am also a freelancer and a Frontend Web Developer with a wide kowledge in html,css,javascript, node.js and react. I have developed several projects and am currently developing more.<br>
         <Br>
          Turning ideas into real life products is my ideal calling. I thank God for helping me achieve this milestone in my web Development career.  Am open for collaboration. Incase you may need me you can contact me throughthe respective platforms which I have hereby attached.
        </div>
        <div class="socails">
          <div class="card">
            <div class="circ">
              <div></div>
            </div>
            <p>Full Name</p>
            <p>Joram Musau</p>
          </div>
          <div class="card">
            <div class="circ">
              <div></div>
            </div>
            <p>Whatsapp me</p>
            <p>
              <a href="http://wa.me/+254740724051">Whatsapp me</a></p>
          </div>
          <div class="card">
            <div class="circ">
              <div></div>
            </div>
            <p>Twitter</p>
            <p><a href="https://twitter.com/messages/1573913037932732416-1573913037932732416?text=">Tweet me</a></p>
          </div>
          <div class="card">
            <div class="circ">
              <div></div>
            </div>
            <p>Instagram</p>
            <p><a href="https://www.instagram.com/direct/t/17842037105863712/">Instagram chat me</a></p>
          </div>
          <div class="card">
            <div class="circ">
              <div></div>
            </div> 
            <p>Phone Number</p>
            <p> <a href="tel:+254740724051">Phone call me</a></p>
          
        </div>
      </section>
      <!-- Services Section -->
      <section class="services" id="services">
        <h2 class="title">What I do</h2>
        <div class="wcards">
          <div class="card">
            <div class="icon"><i class="fa-brands fa-uncharted"></i></div>
            <p class="name">Software Development</p>
          </div>
          <div class="card">
            <div class="icon"><i class="fa-brands fa-dev"></i></div>
            <p class="name">Web Development</p>
          </div>
          <div class="card">
            <div class="icon"><i class="fa-brands fa-unity"></i></div>
            <p class="name">Web <br />Design</p>
          </div>
          <div class="card">
            <div class="icon"><i class="fa-brands fa-apple"></i></div>
            <p class="name">Free <br />Lancing</p>
          </div>
        </div>
        <h2 class="title">My Skills</h2>

        <div class="skillcard">
          <div class="card">
            <div class="per">60%</div>
            <div class="name">Html</div>
          </div>
          <div class="card">
            <div class="per">30%</div>
            <div class="name">Css</div>
          </div>
          <div class="card">
            <div class="per">50%</div>
            <div class="name">javascript</div>
          </div>
          <div class="card">
            <div class="per">40%</div>
            <div class="name">React js</div>
          </div>
        </div>
      </section>
      <!-- Contact Form -->
      <div class="forms">
        <h2 class="title">Get in touch</h2>
        <form action="#">
          <input type="text" placeholder="Name" />
          <input type="text" placeholder="Last name" />
          <input type="text" placeholder="Email" />
          <input type="text" placeholder="Phone number" />
          <input type="text" placeholder="Current location" />
          <textarea
            name=""
            id=""
            placeholder="Message"
            cols="300"
            rows="8"
          ></textarea>
          <a href="#" class="cv">Submit now</a>
        </form>
      </div>
    </main>
    <div>

<form style="margin: 10px;
width: 500px;
background-color: cyan;
border: 5px solid magenta;">
<p style="
background-color: cyan;
border: 5px solid cyan;">
    Rate my character since you came to know me.</p>
<input type="radio"id="Good"
 name="behavior" value="Good">
 <label for="Good">Good</label>
 <br>

 <input type="radio"id="Egocentric"
 name="behavior" value="Egocentric">
 <label for="Egocentric">Egocentric</label>
 <br>

 <input type="radio"id="Bad"
 name="behavior" value="bad">
 <label for="bad">Bad</label>
 <br>

 <input type="radio"id="childish"
 name="behavior" value="childish">
 <label for="childish">Childish</label>
 <br>

 <input type="submit" value="submit">
 
</form></div>

    <footer class="footer">
      &copy;
      <p>Joram Musau</p>
    </footer>
  </body>
</html>
