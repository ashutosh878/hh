<html>
<head>
  <title>span&div</title>
</head>
<body>
   <audio id="audio" src="https://mahdihat791.github.io/v2/test.mp3"></audio>
  <hr>
  <p>
    Span is a inline element.Which means you can arrange elements horizontally side by side.
  </p>
  <hr>
  <span class="sp" onclick="spanelem()">
        <img src = "https://images.unsplash.com/photo-1552727451-6f5671e14d83?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=400&fit=max&ixid=eyJhcHBfaWQiOjE0NTg5fQ">
  </span>
  <span class="sp" onclick="spanelem()">
        <img src = "https://images.unsplash.com/photo-1620905969432-df04fca19ab7?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwxNDU4OXwwfDF8cmFuZG9tfHx8fHx8fHx8MTYyMDk2ODYzNQ&ixlib=rb-1.2.1&q=80&w=400">
  </span>
  <hr>
  <p>Div is block level element. which means you can arrange elements one below the other vertically.</p>
  <div class="di" onclick="divelem()">
    <hr>
    <img src="https://images.pexels.com/photos/462118/pexels-photo-462118.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940">
  </div>
  <div class="di" onclick="divelem()">
    <img src="https://cdn.pixabay.com/photo/2017/01/14/12/59/iceland-1979445_960_720.jpg">
  </div>
  <style type="text/css">
    body{
  text-align: center;
  font-size: 20px;
}

.sp,.di
{
  margin:20px;
}


img{
  width: 20%;
}

  </style>
  <script type="text/javascript">
    function spanelem() {
  window.alert("This is an SPAN element");
}

function divelem() {
  window.alert("This is an DIV element");
  document.getElementById("audio").play();
}


  </script>
</body>
</html>
