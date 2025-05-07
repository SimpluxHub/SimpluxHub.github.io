<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Index</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      height: 100vh;
      overflow: hidden;
      font-family: Arial, sans-serif;
    }

    .background {
      background-image: url('https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/3-Chess-Board.jpg');
      background-size: cover;
      background-position: center;
      filter: blur(8px);
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: -1;
    }

    .content {
      position: relative;
      z-index: 1;
      height: 100%;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 0 0 5px black;
      font-size: 2em;
    }

    .header {
      text-align: center;
      font-size: 2em;
      font-weight: bold;
      margin-top: 50px;
    }

    .footer {
      position: absolute;
      bottom: 10px;
      width: 100%;
      text-align: center;
      font-size: 0.9em;
      color: rgba(255, 255, 255, 0.7);
    }

    .button-container {
      display: flex;
      justify-content: center;
      gap: 15px;
      margin-top: 20px;
    }

    .button {
      background-color: rgba(0, 0, 0, 0.6);
      color: white;
      padding: 10px 20px;
      border-radius: 5px;
      border: none;
      font-size: 1.2em;
      cursor: pointer;
      transition: background-color 0.3s;
    }

    .button:hover {
      background-color: rgba(0, 0, 0, 0.8);
    }

    .links {
      margin-top: 30px;
    }

    .links a {
      color: rgba(255, 255, 255, 0.8);
      font-size: 1em;
      text-decoration: none;
      margin: 0 10px;
    }

    .links a:hover {
      color: rgba(255, 255, 255, 1);
    }

  </style>
</head>
<body>

  <div class="background"></div>
  
  <div class="content">
    <div>
      <div class="header">Welcome to My Index Page</div>
      <div class="button-container">
        <button class="button">Start</button>
        <button class="button">About</button>
      </div>
      <div class="links">
        <a href="#">Link 1</a>
        <a href="#">Link 2</a>
        <a href="#">Link 3</a>
      </div>
    </div>
  </div>

  <div class="footer">
    <p>© 2025 All Rights Reserved</p>
  </div>

</body>
</html>
