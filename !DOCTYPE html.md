<!DOCTYPE html>  
<html>  
<head>  
  <title>Be My Valentine ❤️</title>  
  <style>  
    body {  
      background-color: #ffe6ea;  
      font-family: Arial, sans-serif;  
      text-align: center;  
      padding-top: 100px;  
    }  
    h1 {  
      color: #d6336c;  
      font-size: 40px;  
    }  
    button {  
      font-size: 20px;  
      padding: 12px 25px;  
      margin: 20px;  
      border: none;  
      border-radius: 10px;  
      cursor: pointer;  
    }  
    #yes {  
      background-color: #ff4d6d;  
      color: white;  
    }  
    #no {  
      background-color: #adb5bd;  
      position: absolute;  
    }  
  </style>  
</head>  
  
<body>  
  <h1>Will you be my Valentine? 💖</h1>  
  
  <button id="yes" onclick="yesClick()">YES 💘</button>  
  <button id="no" onmouseover="moveNo()">NO 🙈</button>  
  
  <script>  
    function yesClick() {  
      document.body.innerHTML =  
        "<h1>Yayyy! 💕 I knew it 😍</h1><p>You’re stuck with me now 😘</p>";  
    }  
  
    function moveNo() {  
      alert("Are you sure? 😏 Try again!");  
      let x = Math.random() * (window.innerWidth - 100);  
      let y = Math.random() * (window.innerHeight - 100);  
      document.getElementById("no").style.left = x + "px";  
      document.getElementById("no").style.top = y + "px";  
    }  
  </script>  
</body>  
</html>  
- [ ]   
