<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Arjun's site</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="icon" href="favicon.png">
    <link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Merriweather+Sans&family=Open+Sans&family=Roboto&display=swap" rel="stylesheet">
  </head>
  <body>
    <div class="top-container">
      <img class="top-cloud" src="images/cloud.png" alt="cloud.png">
      <h1>I'am Arjun.</h1>
      <h2>a Programmer.</h2>
      <img class="bottom-cloud" src="images/cloud.png" alt="cloud.png">
      <img src="images/mountain.png" alt="mountain.png">
    </div>
    <div class="middle-container">
      <div class="middle-container">
        <div class="profile">
          <img class="arjun"src="images/arjun.png" alt="arjun.png">
          <h2>Hello.</h2>
          <p class="intro"> I am an ios Developer.I ❤ coffee and brew my own beers.</p>
        </div>
        <hr>
        <div class="skills">
          <h2>My Skills.</h2>
          <div class="skill-row">
            <img class="skill-img" src="images/skills.png" alt="skills.png">
            <h3>Design and Development</h3>
            <p>I started learnig code when i was 20years old because i wanted to make my own video games.Over time i gained a wealth experience in designing developing mobiles and web applications. </p>
          </div>
          <div class="skill-row">
            <img class="chillies-img"src="images/chillies.png" alt="chillies.png">
            <h3>Hot wings Challenge</h3>
            <p>But my best skill is actually in drinking beer.I am undisputed king of hot wing challenges.Non-veg starters are my favourite snacks.</p>
          </div>
        </div>
        <hr>
        <div class="contact-me">
          <h2>Get In Touch</h2>
          <h3>If you love hot wings as much as i do.</h3>
          <p class="contact-message">
           Love hot wings as much i do?Let's talk about how awesome they are!We can code while we eat hot wings!</p>
          <a class="btn" href="mailto:name@email.com">CONTACT ME</a>
        </div>
      </div>


      <div class="bottom-container">
        <a class="footer-link" href="https://www.linkedin.com/">LinkedIn</a>
        <a class="footer-link" href="https://twitter.com/">Twitter</a>
        <a class="footer-link" href="https://www.appbrewery.co/">Website</a>
        <p class="copyright">© 2018 @Arjun Amar </p>
      </div>

    </div>
    <div class="bottom-container">

    </div>
  </body>
</html>
body {
  color: #40514e;
  margin: 0;
  text-align: center;
  font-family: 'Merriweather', serif;
}

h1 {
  color: #66bfbf;
  font-size: 5.625em;
  margin: 50px auto 0 auto;
  font-family: 'Sacromento', cursive;
}

h2 {
  color: #66bfbf;
  font-family: 'Montserrat', sans-serif;
  font-size: 2.5rem;
  font-weight: normal;
  padding-bottom: 10px;
}

h3 {
  color: #11999e;
  font-family: 'Montserrat', sans-serif;
}

p {
  line-height: 2.5;
}

hr {
  border: dotted #eaf6f6 6px;
  border-bottom: none;
  width: 4%;
  margin: 100px auto;
}

a {
  color: #11999e;
  font-family: 'Montserrat', sans-serif;
  margin: 10px 20px;
  text-decoration: none;
}

a:hover {
  color: #eaf6f6;
}

.top-container {
  position: relative;
  padding-top: 100px;
}

.middle-container {
  margin: 100px 0;
}

.bottom-container {
  background-color: #66bfbf;
  padding: 50px 0 20px;
}

.bottom-cloud {
  position: absolute;
  left: 300px;
  bottom: 250px;
}

.top-cloud {
  position: absolute;
  right: 300px;
  top: 40px;
}

.skill-row {
  width: 50%;
  margin: 100px auto;
  text-align: left;
}

.intro {
  width: 30%;
  margin: auto;
}

.contact-message {
  width: 40%;
  margin: 40px auto 60px;
}

.copyright {
  color: #eaf6f6;
  font-size: 0.75rem;
  padding: 20px 0;
}

.skill-img {
  width: 25%;
  float: left;
  margin-right: 30px;
}

.chillies-img {
  width: 25%;
  float: right;
  margin-left: 30px;
}

.btn {
  background: #11cdd4;
  background-image: -webkit-linear-gradient(top, #11cdd4, #11999e);
  background-image: -moz-linear-gradient(top, #11cdd4, #11999e);
  background-image: -ms-linear-gradient(top, #11cdd4, #11999e);
  background-image: -o-linear-gradient(top, #11cdd4, #11999e);
  background-image: linear-gradient(to bottom, #11cdd4, #11999e);
  -webkit-border-radius: 8;
  -moz-border-radius: 8;
  border-radius: 8px;
  font-family: 'Montserrat', sans-serif;
  color: #ffffff;
  font-size: 20px;
  padding: 10px 20px 10px 20px;
  text-decoration: none;
}

.btn:hover {
  background: #30e3cb;
  background-image: -webkit-linear-gradient(top, #30e3cb, #2bc4ad);
  background-image: -moz-linear-gradient(top, #30e3cb, #2bc4ad);
  background-image: -ms-linear-gradient(top, #30e3cb, #2bc4ad);
  background-image: -o-linear-gradient(top, #30e3cb, #2bc4ad);
  background-image: linear-gradient(to bottom, #30e3cb, #2bc4ad);
  text-decoration: none;
}
