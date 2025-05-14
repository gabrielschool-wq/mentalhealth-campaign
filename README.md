<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mental Health Matters</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(120deg, #e0f7fa, #fff);
      color: #333;
      margin: 0;
      padding: 0;
    }

    header {
      background: linear-gradient(90deg, #00bcd4, #0097a7);
      color: white;
      padding: 30px 20px;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }

    nav {
      background-color: #b2ebf2;
      padding: 15px 0;
      text-align: center;
    }

    nav a {
      margin: 0 20px;
      text-decoration: none;
      color: #006064;
      font-weight: bold;
      font-size: 16px;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 30px 20px;
      border-bottom: 1px solid #ccc;
    }

    section h2 {
      color: #00796b;
    }

    ul {
      padding-left: 20px;
    }

    footer {
      background-color: #00acc1;
      color: white;
      text-align: center;
      padding: 20px;
      box-shadow: 0 -2px 10px rgba(0, 0, 0, 0.1);
    }

    .footer-socials {
      margin-top: 10px;
    }

    .footer-socials a {
      display: inline-block;
      margin: 0 10px;
    }

    .footer-socials img {
      width: 30px;
      height: 30px;
      filter: brightness(0) invert(1);
    }

    .team {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }

    .team-member {
      text-align: center;
      max-width: 200px;
      background-color: #e0f2f1;
      border-radius: 10px;
      padding: 15px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    }

    .team-member img {
      width: 100%;
      height: auto;
      border-radius: 10px;
      border: 3px solid #4db6ac;
    }

    .uniform-section {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      margin-top: 20px;
    }

    .uniform-section img {
      width: 30%;
      margin: 10px;
      border-radius: 8px;
      box-shadow: 2px 2px 5px rgba(0,0,0,0.1);
    }

    .center-text {
      text-align: center;
      margin: 20px auto;
      max-width: 800px;
      font-size: 1.1em;
    }

    .video-container {
      display: flex;
      justify-content: center;
      padding: 20px;
    }

    iframe {
      width: 90%;
      max-width: 700px;
      height: 400px;
      border: none;
      border-radius: 10px;
    }

    .story, .qa {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
      background: #e0f2f1;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    .story h3, .qa h3 {
      color: #00695c;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mental Health Matters</h1>
    <p>Promoting awareness, support, and action</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#stigma">Break the Stigma</a>
    <a href="#resources">Get Help</a>
    <a href="#action">Take Action</a>
    <a href="#team">About Us</a>
    <a href="#partners">Our Work</a>
    <a href="#uniform">Uniform</a>
    <a href="#founders">Founders</a>
    <a href="#video">Campaign Video</a>
  </nav>

  <section id="about">
    <h2>About Mental Health</h2>
    <p>Mental health includes our emotional, psychological, and social well-being. It affects how we think, feel, and act. Taking care of our mental health is just as important as taking care of our physical health.</p>
  </section>

  <section id="stigma">
    <h2>Breaking the Stigma</h2>
    <p>Many people are afraid to talk about mental health. Our goal is to normalize these conversations, spread accurate information, and support those who may be struggling. Let's make it okay to not be okay.</p>
  </section>

  <section id="resources">
    <h2>Get Help</h2>
    <ul>
      <li><strong>School Counselor:</strong> Talk to your school counselor anytime you feel overwhelmed.</li>
      <li><strong>988 Suicide & Crisis Lifeline:</strong> Call or text 988 for free and confidential help.</li>
      <li><strong>National Alliance on Mental Illness (NAMI):</strong> <a href="https://www.nami.org" target="_blank">www.nami.org</a></li>
    </ul>
  </section>

  <section id="action">
    <h2>Take Action</h2>
    <p>You can help by being kind, listening without judgment, and speaking up when you see someone struggling. Share resources, start conversations, or organize a school event to raise awareness.</p>
  </section>

  <section id="team">
    <h2>About Us</h2>
    <p>Meet the team behind the Mental Health Matters campaign:</p>
    <div class="team">
      <div class="team-member">
        <img src="https://i.imgur.com/j6O4Klu.jpeg" alt="Ben">
        <p><strong>Ben</strong><br>Creative Lead</p>
      </div>
      <div class="team-member">
        <img src="https://i.imgur.com/VTS9M9f.jpeg" alt="Max">
        <p><strong>Max</strong><br>Technical Director</p>
      </div>
      <div class="team-member">
        <img src="https://i.imgur.com/2Er0Oeu.jpeg" alt="Gabriel">
        <p><strong>Gabriel</strong><br>Event Coordinator</p>
      </div>
    </div>
  </section>

  <section id="partners">
    <h2>Our Previous Work</h2>
    <p>We’ve collaborated with leading organizations to expand our impact and reach:</p>
    <ul>
      <li><strong>Gatorade:</strong> Sponsored a wellness workshop series for student athletes.</li>
      <li><img src="https://i.ebayimg.com/00/s/NjkzWDUyNQ==/z/u0QAAOSwufRm7kHW/$_57.JPG?set_id=8800005007" alt="Gatorade Poster" width="200"></li>
      <li><strong>Nike:</strong> Partnered on a youth resilience campaign promoting active mental health habits.</li>
      <li><strong>Google:</strong> Helped develop an educational resource hub on YouTube for mental health awareness.</li>
    </ul>
  </section>

  <section id="uniform">
    <h2>Uniform</h2>
    <div class="center-text">
      <p><strong>We value our employees' comfort because we believe they work best and are most creative when comfortable.</strong></p>
    </div>
    <div class="uniform-section">
      <img src="https://images.unsplash.com/photo-1588776814546-ec03f29c4c09" alt="Uniform 1">
      <img src="https://images.unsplash.com/photo-1600185365929-3f494a4d3c9f" alt="Uniform 2">
      <img src="https://images.unsplash.com/photo-1520975922203-6ca4a1b66703" alt="Uniform 3">
    </div>
  </section>

  <section id="founders">
    <div class="story">
      <h3>Our Story</h3>
      <p>We founded GURT.inc because we saw a gap in how mental health was treated in schools and communities. Starting in a garage with just an idea, we’ve grown into a campaign working with some of the world’s most recognized brands.</p>
    </div>

    <div class="qa">
      <h3>Q&A with the Founders</h3>
      <p><strong>Q:</strong> What motivated you to start this campaign?<br><strong>A:</strong> Personal experiences and seeing friends struggle inspired us to create something real and supportive.</p>
      <p><strong>Q:</strong> What's next for GURT.inc?<br><strong>A:</strong> Expanding into more schools and building tech tools to support mental health 24/7.</p>
    </div>
  </section>

  <section id="video">
    <h2>Our Campaign Video</h2>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/JdMmBY5L0ow?si=gb4sKGoQV122ll5G" allowfullscreen></iframe>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Mental Health Awareness Campaign | Powered by <strong>GURT.inc</strong></p>
    <div class="footer-socials">
      <a href="https://www.instagram.com/" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram" /></a>
      <a href="https://twitter.com/" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/en/6/60/Twitter_Logo_as_of_2021.svg" alt="Twitter" /></a>
      <a href="https://www.youtube.com/" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/9/9f/Youtube%28amin%29.png" alt="YouTube" /></a>
    </div>
  </footer>
</body>
</html>
