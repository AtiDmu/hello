<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>I Love You Gradient</title>
  <style>
    body {
      height: 100vh;
      margin: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      background: linear-gradient(to right, black, rgb(223, 116, 208));
      font-family: Arial, sans-serif;
    }

    .circle-container {
      width: 250px;
      height: 250px;
      border-radius: 50%;
      overflow: hidden;
      border: 6px solid white;
      box-shadow: 0 6px 20px rgba(0, 0, 0, 0.4);
      margin-bottom: 30px;
    }

    .circle-container img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .text {
      font-size: 8vw;
      font-weight: bold;
      color: white;
      text-align: center;
      text-shadow: 
        3px 3px 0px rgba(0, 0, 0, 0.2),
        6px 6px 0px rgba(0, 0, 0, 0.2),
        9px 9px 0px rgba(0, 0, 0, 0.2),
        12px 12px 0px rgba(0, 0, 0, 0.2),
        15px 15px 0px rgba(0, 0, 0, 0.2);
    }

    @media (max-width: 480px) {
      .text {
        font-size: 12vw;
      }
      .circle-container {
        width: 180px;
        height: 180px;
      }
    }
  </style>
</head>
<body>
  <div class="circle-container">
    <img src="https://raw.githubusercontent.com/AtiDmu/Elda/main/elda/dmu.jpg" alt="DMU Image" />
  </div>

  <div class="text">
    I love you so much ati dmu
  </div>
</body>
</html>
