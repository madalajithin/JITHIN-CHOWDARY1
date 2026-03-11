# JITHIN-CHOWDARY

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>JITHIN CHOWDARY</title>

<style>

body{
margin:0;
padding:0;
font-family: Arial, sans-serif;
background:black;
color:white;
text-align:center;
overflow-x:hidden;
}

/* PARTICLES BACKGROUND */

#particles-js{
position:fixed;
width:100%;
height:100%;
top:0;
left:0;
z-index:-1;
}

/* CONTAINER */

.container{
margin-top:80px;
}

/* PROFILE */

.profile{
width:120px;
height:120px;
border-radius:50%;
border:4px solid gold;
box-shadow:0 0 20px gold;
}

/* TITLE */

.title{
font-size:40px;
margin-top:20px;
letter-spacing:3px;
color:#00ffff;
text-shadow:0 0 10px #00ffff,0 0 20px #00ffff;
}

/* BIO */

.bio{
opacity:0.8;
margin-bottom:30px;
}

/* LINKS */

.links{
width:280px;
margin:auto;
}

/* NEON BUTTONS */

.btn{
display:block;
text-decoration:none;
padding:14px;
margin:12px 0;
border-radius:10px;
font-weight:bold;
color:white;
border:2px solid #00ffff;
background:transparent;
transition:0.3s;
box-shadow:0 0 10px #00ffff;
}

.btn:hover{
background:#00ffff;
color:black;
box-shadow:0 0 20px #00ffff,0 0 40px #00ffff;
transform:scale(1.05);
}

.footer{
margin-top:40px;
opacity:0.6;
}

</style>

</head>

<body>

<div id="particles-js"></div>

<div class="container">

<img src="aa2538c5-8cea-4b39-b49f-490e9cc2077c.png" class="profile">

<h1 class="title"><span id="typing"></span></h1>

<p class="bio">Welcome to my website 🚀</p>

<div class="links">

<a href="https://www.instagram.com/jithin_chowdary_" class="btn" target="_blank">Instagram</a>

<a href="https://youtube.com/@jithingamingyt-i2l" class="btn" target="_blank">YouTube - Jithin Gaming</a>

<a href="https://discord.gg/mtK2PSg6uP" class="btn" target="_blank">Join My Discord Server</a>

<a href="https://discord.com/users/1267791203781443634" class="btn" target="_blank">My Discord Profile</a>

<a href="https://github.com/madalajithin/JITHIN-CHOWDARY" class="btn" target="_blank">GitHub</a>

<a href="https://www.snapchat.com/add/madala_jithin?share_id=w8HRt1b6hOg&locale=en-US" class="btn" target="_blank">Snapchat</a>

</div>

<div class="footer">
© 2004 Jithin Chowdary
</div>

</div>

<!-- PARTICLES JS -->

<script src="https://cdn.jsdelivr.net/npm/particles.js"></script>

<script>
particlesJS("particles-js", {
  particles: {
    number: { value: 100 },
    color: { value: "#00ffff" },
    shape: { type: "circle" },
    opacity: { value: 0.5 },
    size: { value: 3 },
    line_linked: {
      enable: true,
      distance: 150,
      color: "#00ffff",
      opacity: 0.4,
      width: 1
    },
    move: {
      enable: true,
      speed: 2
    }
  }
});
</script>

<!-- TYPING ANIMATION -->

<script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>

<script>
var typed = new Typed("#typing", {
  strings: [
    "JITHIN CHOWDARY",
    "WELCOME TO MY WEBSITE",
    "GAMER • DEVELOPER"
  ],
  typeSpeed: 60,
  backSpeed: 40,
  loop: true
});
</script>

</body>
</html>
