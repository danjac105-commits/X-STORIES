<!DOCTYPE html>
<html>
<head>
<title>TechMagic Stories</title>

<style>

body{
margin:0;
height:100vh;
overflow:hidden;
background:#030712;
font-family:Arial;
}

.book{
position:absolute;
top:50%;
left:50%;
transform:translate(-50%,-50%);
width:350px;
height:220px;
background:linear-gradient(45deg,#00ffff,#0066ff);
border-radius:20px;
box-shadow:0 0 60px cyan;
animation:float 3s infinite ease-in-out;
}

@keyframes float{
50%{
transform:translate(-50%,-55%);
}
}

.magic{
position:absolute;
color:white;
font-size:30px;
animation:rise 6s linear infinite;
}

@keyframes rise{
from{
transform:translateY(0);
opacity:1;
}
to{
transform:translateY(-500px);
opacity:0;
}
}

.menu{
position:absolute;
top:30px;
right:30px;
}

button{
padding:12px 25px;
margin:5px;
border:none;
border-radius:10px;
background:#00ffff;
cursor:pointer;
font-weight:bold;
}

</style>

</head>
<body>

<div class="book"></div>

<div class="magic" style="left:48%;top:40%;">
READ
</div>

<div class="magic" style="left:52%;top:45%;">
MORE
</div>

<div class="magic" style="left:45%;top:42%;">
AND LEARN
</div>

<div class="menu">
<button onclick="location.href='signup.html'">
Sign Up
</button>

<button onclick="location.href='membership.html'">
Membership
</button>

<button onclick="location.href='write.html'">
Write
</button>

<button onclick="location.href='stories.html'">
Our Stories
</button>
</div>

</body>
</html>
<div
# X-STORIES
</div>
