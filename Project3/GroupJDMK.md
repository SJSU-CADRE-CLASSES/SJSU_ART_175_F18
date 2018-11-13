http://jasonmanzon.com/home.html 

Jason, Dan, Martin, and Krystal 

For Project 3, our group focused on creating a unique soundscape through the results of a survey from the audience. The idea behind the project was to not only gather people online but also to have them contribute together to create a physical soundscape together.  

Jason: Created final 3 result aFrame pages pieced webpages together. 

Dan: 
Provided code for the outline for the html and css for the survey questionnaire. Then sent the .css and .html file to Martin so he can input Crystal and his own questions/answers on the survey. Martin successfully created 7 identical survey websites. The concept behind this idea was to use a survey to gather people together to create a output that results with sounds, ideally in a gallery setting. The installation would have 3 possible outcomes already playing in the environment depicting 3 natural themes. People are given similar but different survey questions that hopefully balance the outcomes. 

Provided code to Martin: 

<!DOCTYPE html>
<html>

  <head>
      <meta charset="utf-8">
     <link rel="stylesheet" type="text/css" href="css/proj4.css">
      <title>About</title>
  </head>


<body>

  <div id="main">

    <center>
      <h2>What is your favorite chicken?</h2>


      <div id="content">
        <div id="portfolio">
            <a href="portfolio/roots.html"><img src="media/vx1000ban.jpg" alt="roots.html"></a>
            <a href="portfolio/unity.html"><img src="media/unityban.jpg" alt="unity.html"></a>
            <a href="portfolio/james.html"><img src="media/james.jpg" alt="james.html"></a>
         </div>   
      </div>
    </center>

  </div>  
</body>  
</html>

@import url('https://fonts.googleapis.com/css?family=Special+Elite');
@import url('https://fonts.googleapis.com/css?family=Ubuntu');

* {
    margin:0;
    padding: 0;
}

body {
    width:100%;
    height:100%;
    background-color: #F2F1EF;
}

.fullscreen-bg {
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    overflow: hidden;
    z-index: -100;
}

.fullscreen-bg__video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100vw;
    height: auto;
    z-index: -1000;

}

.text {
    position: absolute;
    top: 200px;
    left: 200px;
    overflow: hidden;
    z-index: 100;
    opacity: 0.5;
    font-family: 'Special Elite';
    padding:0px .0px;
}

a h1 {
    color: #000;
    text-decoration: none;
    opacity: 1;
    letter-spacing: 6px;
}

#main {
    margin-top: 40px;
    font-family: 'Ubuntu', sans-serif;
}

#links {
    margin-top: 40px;
    margin-bottom: 40px;
}

#links a {
    width:100px;
    padding:10px;
    border: 2px solid #ddd;
    margin-right: 10px;
    color:#aaa;
    text-decoration: none;
    transition: all .5s ease;
}

#links a:hover {
    background-color: #ddd;
    color:#fff;
    transition:all .5s ease;
}

#content {
    background-color: #F2F1EF;
    width: 100vw;
    padding-top:40px;
    padding-bottom:40px;
}

#content p {
    width:700px;
    text-align: justify;
}



#portfolio a img {
    margin-bottom:10px;
}


