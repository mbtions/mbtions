<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
      @import url("https://fonts.googleapis.com/css2?family=Comforter+Brush&family=Estonia&family=Montserrat:wght@300&family=Open+Sans:wght@300&family=Outfit:wght@100;200;300;400&family=Poppins:wght@100;200;400&family=Roboto+Condensed:wght@300&display=swap");
      * {
        margin: auto;
        padding: auto;
        font-family: "Open Sans";
      }

      .container {
        margin: 10px;
      }

      .nav_header {
        display: flex;
        justify-content: center;
        align-items: center;
        background: rgba(70, 70, 70, 0.3);
      }
      #logo {
        font-family: Comforter Brush;
        font-size: xx-large;
      }
      .nav_header ul {
        list-style: none;
      }
      .nav_links {
        float: left;
        padding: 5px;
        margin: 5px;
      }
      .about h1 {
        text-align: center;
      }
      .about_card {
        margin: 10px;
        font-family: monospace;
        font-size: large;
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        border: 0.5px solid #4287f5;
        border-radius: 5px;
        background-image: linear-gradient(#4287f5, #92b6f0);
        text-align: center;
      }
      .about_card p {
        margin: 20px;
        color: white;
      }
      .about span {
        color: goldenrod;
      }
      .about img {
        margin: 10px;
        width: 30%;
        height: 30%;
        border-radius: 50%;
        border: 2px solid #4287f5;
      }
      .socials {
        margin: 0;
        padding: 10px;
        text-align: center;
        background: rgba(0, 0, 0, 1);
      }
      .socials {
        color: white;
      }
      .socials p {
        margin: 3px;
        padding: 5px;
        font-size: large;
      }
      .socials a {
        margin: 5px;
        padding: 10px;
        text-decoration: none;
        color: white;
      }
      #academic {
        border: 2px solid rgb(70, 70, 70);
        text-align: center;
      }
      td,
      th {
        padding: 5px;
        border: 1px solid rgb(70, 70, 70);
      }
      .footer_default {
        margin: 0;
        padding: 20px;
        text-align: right;
        color: white;
        background: #000;
      }
    </style>
</head>
<body>
    <div class="nav_header">
  <h3 id="logo">MBtions</h3>
  <ul>
    <li class="nav_links">About</li>
    <li class="nav_links">Projects</li>
    <li class="nav_links">Interests</li>
    <li class="nav_links">Socials</li>
  </ul>
</div>

<div class="container about" id="about_me">
  <h1>Hello, I'm <span>Meenakshi</span></h1>
  <div class="about_card">
    <p>Learner | Web Development | Open Source Enthusiast </p>
    <img id="profile_img" src="https://avatars.githubusercontent.com/u/59952791?v=4">
  </div>
  <ul>
    <li>Pursuing <b>BSc (Hons.) Computer Science</b> from University of Delhi.</li>
    <li>Developed interest in web development in 2016 during summer vacations.</li>
    <li>What I build and learned during pandemic quarantine -
      <ol>
        <li>Joined a bootcamp on Machine Learning</li>
        <li>Build Invisible Cloak ML Project</li>
        <li>Joined <b>The Uplift Project</b> program by <em>The GirlScript Foundation</em> to develop skills in android tech stack.</li>
        <li>Did a Research paper on pre-trained transformers based Deep NLP models for Text Summarization Web Application.</li>
      </ol>
    </li>
    <li>Academic Qualification
      <table id="academic">
        <tr>
          <th>TableHeading1</th>
          <th>TableHeading2</th>
          <th>TableHeading3</th>
          <th>TableHeading4</th>
        </tr>
        <tr>
          <td>data1</td>
          <td>data2</td>
          <td>data3</td>
          <td>data4</td>
        </tr>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        </tr>
        <tr>
          <td>will</td>
          <td>update</td>
          <td>it</td>
          <td>soon!</td>
        </tr>
      </table>

    </li>
  </ul>
</div>
<div class="container" id="my_projects">

</div>

<div id="my_interests" class="container interests">
  <h3>My Interests are:</h3>
  <ul>
    <li>Web Development</li>
    <li>Data Science, AI & ML</li>
    <li>Mobile Development</li>
    <li>Firebase</li>
    <li>Open Source</li>
    <li>Blogging</li>
  </ul>
</div>

<div id="my_socials" class="container socials">
  <p>Let's connect</p>
  <a href="" target="blank_"><i class="fa fa-facebook" style="font-size: 20px; padding: 5px;"></i></a>
  <a href="https://twitter.com/mbtions" target="blank_"><i class="fa fa-twitter" style="font-size:20px; padding:5px"></i></a>
  <a href="https://github.com/MBtions" target="blank_"><i class="fa fa-github" style="font-size:20px; padding:5px"></i></a>
  <a href="https://linkedin.com/in/MBtions" target="blank_"><i class="fa fa-linkedin" style="font-size:20px; padding:5px"></i></a>
</div>

<div class="container footer_default">
  <p><i class="fa fa-copyright" style="font-size:15px; padding:5px"></i> 2021 MBtions</p>
</div>
</body>
</html>
