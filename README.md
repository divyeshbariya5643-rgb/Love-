<!DOCTYPE html>
<html>
<head>
<title>Proposal</title>
</head>
<body style="background:#111;color:white;text-align:center;padding-top:100px;font-family:sans-serif;">

<script>
const p = new URLSearchParams(window.location.search);
const me = p.get("me");
const love = p.get("love");
</script>

<h1 id="text">💖 Love Proposal 💖</h1>

<script>
if(me && love){
  document.getElementById("text").innerHTML =
    love + " ❤️<br>" + me + " loves you forever<br><br>Will you marry me? 💍";
}
</script>

</body>
</html>
