<!DOCTYPE html>
<html>
<head>
  <title>IT 勉強用サイト</title>

  <style>
    body {
      background: lightblue(to right, #667eea, #764ba2);
      font-family: "Times New Roman";
      margin: 0;
      padding: 0;
      text-align: center;
      color: black;
    }

    .container {
      margin-top: 50px;
    }

    h1 {
      font-size: 40px;
      margin-bottom: 10px;
    }

    p {
      font-size: 18px;
      margin: 5px;
    }

    img {
      display: block;
      margin: 20px auto;
      width: 200px;
      border-radius: 50%;
      border: 4px solid white;
      transition: 0.3s;
    }

    img:hover {
      transform: scale(1.1);
    }

    button {
      margin-top: 20px;
      padding: 10px 20px;
      font-size: 16px;
      border: none;
      border-radius: 10px;
      background-color: white;
      color: #764ba2;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background-color: #ddd;
    }
  </style>
</head>

<body>
  <div class="container">
    <h1>Nguyễn Tất Trung</h1>
    <p>Đây là website đầu tiên của tôi</p>
    <p>Tôi sẽ học IT để làm màu với vợ tôi 😎</p>

    <img src="a.jpg">

    <button onclick="hello()">Bấm vào đây</button>
  </div>

  <script>
    function hello() {
      alert("Xin chào Thu Mắm, trưa nay ăn cơm với gì thế em? ");
    }
  </script>
</body>
</html>
