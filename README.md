<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Nensi ❤️</title>

<style>
body{
margin:0;
font-family:Arial;
text-align:center;
background:linear-gradient(135deg,#ff758c,#ff7eb3);
color:white;
overflow:hidden;
}
h1{margin-top:40px;}
p{padding:20px;font-size:18px;}

img{
width:85%;
border-radius:20px;
margin:10px;
box-shadow:0 0 20px rgba(0,0,0,0.3);
}
.heart{
position:fixed;
top:-10%;
color:red;
animation:fall linear infinite;
}
@keyframes fall{
0%{transform:translateY(-10%);}
100%{transform:translateY(110%);}
}
</style>
</head>

<body>

<h1>Happy Birthday Nensi ❤️</h1>

<p>
You are the reason behind my smile 💖<br><br>
Every moment with you feels magical ✨<br><br>
Stay happy always 😊<br><br>
Forever Yours,<br>
Nevil ❤️
</p>

<script>
for(let i=0;i<30;i++){
let heart=document.createElement("div");
heart.innerHTML="❤️";
heart.className="heart";
heart.style.left=Math.random()*100+"%";
heart.style.fontSize=(Math.random()*20+10)+"px";
heart.style.animationDuration=(Math.random()*3+2)+"s";
document.body.appendChild(heart);
}
</script>

</body>
</html>
