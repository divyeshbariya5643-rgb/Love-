<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Love Proposal 💍</title>

<style>
body{
    margin:0;
    height:100vh;
    font-family:'Segoe UI',sans-serif;
    background:radial-gradient(circle at top,#ff7eb3,#0f051d);
    display:flex;
    align-items:center;
    justify-content:center;
    overflow:hidden;
    color:white;
}
.container{
    background:rgba(255,255,255,0.12);
    backdrop-filter:blur(12px);
    border-radius:25px;
    padding:30px;
    text-align:center;
    width:330px;
    box-shadow:0 25px 50px rgba(255,0,100,0.4);
    z-index:10;
}
input{
    width:90%;
    padding:12px;
    margin:8px 0;
    border-radius:12px;
    border:none;
    font-size:16px;
}
button{
    padding:12px 28px;
    border:none;
    border-radius:40px;
    font-size:16px;
    cursor:pointer;
    margin:10px;
}
.yes{
    background:linear-gradient(45deg,#00ffcc,#00c896);
    color:#003333;
}
.no{
    background:linear-gradient(45deg,#ff4d4d,#ff1a1a);
    color:white;
    position:relative;
}
.create{
    background:linear-gradient(45deg,#ff2d75,#ff6fa5);
    color:white;
}
.glow{
    animation:glow 2s infinite alternate;
}
@keyframes glow{
    from{text-shadow:0 0 10px #ff4e8a;}
    to{text-shadow:0 0 25px #ffb3d9;}
}
canvas{
    position:fixed;
    inset:0;
    z-index:1;
}
</style>
</head>

<body>

<canvas id="fireworks"></canvas>

<div class="container" id="formBox">
    <h2 class="glow">💖 Create Proposal 💖</h2>
    <input id="me" placeholder="Your Name">
