<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> Web Development</title>
</head>
<body>
  <nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="contact.html">Contact</a>
  </nav>
<h1>HOME PAGE</h1>
<h2>BSIT 1A</h2>
<h2>These are our Graduation Pictures</h2>
 <style>
    .image-row {
      display: flex;
      gap: 20px;
      align-items: center;
    }
    .image-row div {
      text-align: center;
    }
  </style>
</head>
<body>
  <div class="image-row">
    <div>
      <img src="https://image2url.com/r2/default/images/1772161100826-6b7981c2-6ae9-4f17-bea7-5f1554ad1777.jpg" 
           alt="Torres_Mardon Lale" width="200" height="200">
      <p>Torres, Mardon Lale D.</p>
    </div>
    <div>
      <img src="https://image2url.com/r2/default/images/1772164410925-36269cde-3192-4dfc-b4d4-8f25cf238aec.jfif" 
           alt="Basubas_Ahya" width="200" height="200">
      <p>Basubas, Ahya</p>
    </div>
  </div>

  <h2>EXPLANATION IN AUDIO FORM</h2>
  <audio controls>
    <source src="https://image2url.com/r2/default/videos/1772185847799-684cd240-52c8-4a38-9c62-65322b375b30.mp4" type="audio/mp3">
  </audio>

  <br>

  <video width="400" controls>
    <source src="https://image2url.com/r2/default/videos/1772108935756-a466b2fc-52f6-48ca-8abb-2d4bc2de5d27.mp4" type="video/mp4">
  </video>
</body>
</html>
