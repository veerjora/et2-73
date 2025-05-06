# et2-73
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>   
    * {
      padding: 3px
      margin: 4px; 
      /* background-color: #2ee68d; */
      background-color: #15e3b7;
    }
     div.logo {
        font-size: 24px;
        font-weight: bold;
        color: #ae2922;
        underline : 2px solid rgba(0, 0, 0, 0.493);
        text-decoration: underline;
    }
    h1, h2 {
        font-size h1 : 25px;
        font-size h2 : 20px;
        color: #a20a0a;
        underline : 2px solid rgba(0, 0, 0, 0.493);
        text-decoration: underline;
    }
  p {
    font-size: 17px;
    font-style: normal;
    color: rgb(0, 0, 0);

  }
    
    h3 {
        font-size: 18px;
        color: #000000
        
    }
    div.project-list {
        background-color: #f4f4f4
        border-radius: 5px;
        /* underline : 2px solid rgba(0, 0, 0, 0.493);
        text-decoration: underline; */
    }
    video {
      padding: 1px;
      margin: 1px;
     height: 290px;
     
    }
    <style>
  .image-crop {
    width: 230px; /* Desired width of the cropped area */
    height: 250px; /* Desired height of the cropped area */
    overflow: hidden;
    border-radius: 50%; /* Optional: Makes the cropped area circular */
  }

  .image-crop img {
    width: 35%; /* Adjust as needed */
    height: 100%; /* Maintain aspect ratio */
    object-fit: cover; /* Ensures the image fills the cropped area */
    </style>
</head>
<body>
    <header>
        <nav class="navbar">
          <div class="logo">My Portfolio</div>
          <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
      
      
          </ul>
        </nav>
      </header>
    
      <section class="hero">
        <h1>Hi, I am  Veer</h1>
        <p>A student in MitAoe from 1st year, pursuing Btech degree from ENTC department from ET2 division and E-24 batch. </p>
      </section>
    
      <section id="about" class="about">
        <h2>About Me</h2>
        <div class="image-crop">
          <img src="meeh.jpg" alt="My Image">
        </div>
        <p>I am a college student who loves upgrading his skills and to explore new things, i mostly like to do editing of videos and photos. I am also interested in learning new programming languages and web development. I also post my video editing in the form of reels in Instagram and i am also part of a photography club in my college named as "Shutterbugs". </p>
        Some of my hobbies are: 
        <nav>
          <ul>
            <li>planting</li>
            <li>I love old model bikes</li>
            <li>cooking</li>
        </nav>
        <p>  </p>
      </section>
    
      <section id="skills" class="skills">
        <h2>Skills</h2>
        <ul>
          <li>HTML</li>
          <li>CSS</li>
          <li>C++</li>
          <li>VIDEO EDITING</li>
          <li>PHOTO EDITING</li>
          <li>PHOTOGRAPHY</li>
        </ul>
      </section>
    
      <section id="projects" class="projects">
        <h2>Projects</h2>
        <div class="project-list">
          <div class="project">
            <h3>Project 1</h3>
            <p> Video Editing: With the help of software called "Capcut" i had edited a video. </p>
           <video src="edit.mp4" controls loop muted poster="nature.jpg"></video>
        <audio src="edit audio.mp3"></audio>
          <div class="project">
            <h3>Project 2</h3>
            <p> Video Editing of MitAdt </p>
            <video src="edit 1.mp4"  controls loop muted poster="adt.png"></video>
          </div>
          <p> Here are my some photographs</p>
           <img src="pi" alt="">
        </div>
      </section>
    
      <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <p>Email: 202401070209@mitaoe.ac.in </p>
        <p> GitHub | Twitter</p>
      </section>
    
      <footer>
        <p>&copy; 2025 Veer Jora. All rights reserved.</p>
      </footer>

</body>
</html>
