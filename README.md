# 05.12.21-Sample-Coding
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <link href="style.css" rel="stylesheet" type="text/css">
    <title>First HTML Website Practice</title>
  </head>
  <body>
    <nav>
    <div class="main-heading">
      <h1>Madelyn Bonzi's First Practice for HTML and CSS Coding</h1>
    </div>
    <div class="rel-path-head">
      <ul>
        <li><a href="#Welcome">Welcome!</a></li>
        <li><a href="#About_Me">About Me</a></li>
        <li><a href="#Curriculum">Web Developer Curriculum</a></li>
      </ul>
    </div>
  </nav>
    <br>
    <div class="heading-two">
      <h2 id="Welcome">Welcome to my page! </h2>
    </div>
    <div class="free-text">
      <p>This is the beginning of my coding career. I hope you enjoy seeing my initial progress and where I go from here!</p>
    </div>

    <div class="heading-two">
      <h2 id="About_Me">About Me</h2>
    </div>
    <div class="free-text">
      <p>
        If you were anything like me, when you graduated high school there were so many career fields that interested you that you could not pick just one.
        Not knowing exactly what I wanted to do, I enrolled in a community college in my local town while working two jobs simultaneously.
        I enrolled in courses for a math major, psychology major, fire, and EMT.
        If I didn't know what I wanted when I started undergraduate schooling, let me tell you that I was only getting for confused with every additional course that I enrolled in.
        By the time that I graduated, I had received two promotions, one at each job, and 4 Associates Degrees.
        I then transferred to a community college in Central California where I obtained one more degree within the next year, an AA-T in Kinesiology.
        This degree allowed my to transfer to California Polytechnic University in San Luis Obispo, California.
        After two years of working full-time and attending school full-time, I obtained a Bachelor of Science degree in Kinesiology.
        <br>
        This degree propelled me towards my career in healthcare.
        Since graduating, I have worked at an orthopedic surgery clinic which utilizes my knowledge from school, personal training and experience from working at a physical therapy clinic.
        This career has increased my ability to lead a staff, work within a team environment, multitask, and maintain a clear thought-process while under pressure.
        What I did not expect to learn is that what I truly excelled at and enjoyed was organizing, editing, and entering data into our electronic medical record (EMR) systems.
        This part of the job is often described as <em>tedious but necessary</em>; however is what allowed me to finally make an informed decision on the future of my career.
        <br>
        <strong> I am very excited for my future in program development and coding!!</strong>
      </p>
      <br>
    </div>

    <div class="heading-two">
      <h2 id="Curriculum">Web Developer Curriculum and Tools</h2>
    </div>
    <div class="free-text">
      <form class="dropdown-list" action="index.html" method="post">
        <label for="courses">Coding & Programming Courses and Certificates:</label>
        <select class="courses" name="courses" id="codecademy-courses">
          <option value="HTML-into">Introduction to HTML</option>
          <option value="css-into">Introduction to CSS</option>
          <option value="css-intermediate">Intermediate CSS</option>
          <option value="css-advanced">Advanced CSS Grids</option>
          <option value="ATOM">ATOM</option>
        </select>
      </form>
    </div>
    <div class="free-text">
      <form class="dropdown-list" action="index.html" method="post">
        <label for="next-courses">Next Steps in My Education:</label>
        <select class="next-courses" name="next-courses" id="future-courses">
          <option value="Javascript">Javascript</option>
          <option value="Git">Git</option>
          <option value="GitHub">GitHub</option>
          <option value="React">React</option>
          <option value="Python">Python</option>
        </select>
      </form>
    </div>
  </body>
</html>
