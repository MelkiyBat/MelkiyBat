<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
  {
  margin: 0;
  padding: 0;
  text-decoration: none;
  list-style: none;
  font-family: "Open Sans",sans-serif;
}

body{
  display: flex;
  height: 100vh;
  background-color: black;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.menu a{
  display: inline-block;
  margin: 30px;
  padding: 12px 60px;
  color: #f1f1f1;
  text-transform: uppercase;
  font-size: 30px;
  font-weight: 600;
  transition: .3s linear;
  position: relative;
}

.menu a:hover{
  color: white;
}

.menu a::before,
.menu a::after{
  content: "";
  position: absolute;
  width: 100%;
  height: 0%;
  left: 0;
  box-sizing: border-box;
  z-index: -1;
}



.menu a::after{
  top: 0;
  box-shadow: 0 0 10px #9baff1, 0 0 40px #9baff1;
  background-color: #b9c9fe;
  transition: .3s linear .3s;
}

  </style>
</head>
<body>
  <ul class="menu">
    <li><a href="C:\Users\а\Desktop\Create\Glavnaya.html">главная</a></li>
    <li><a href="C:\Users\а\Desktop\Create\Боссы\tableboss.html">боссы</a></li>
    <li><a href="C:\Users\а\Desktop\Create\Реалмы\realm.html">реалмы</a></li>
    <li><a href="#">связь</a></li>
  </ul>

</body>
</html>
