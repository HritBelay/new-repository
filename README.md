<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="style.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f8ff; /* light blue background */
      color: #333;
      line-height: 1.6;
      padding: 20px;
    }

    h1 {
      color: #ff4500; /* orange-red */
      text-align: center;
      border-bottom: 3px solid #ff4500;
      padding-bottom: 10px;
    }

    h2 {
      color: #1e90ff; /* dodger blue */
      margin-top: 30px;
    }

    .plaintext {
      color: #32cd32; /* lime green */
      font-style: italic;
    }

    p {
      font-size: 16px;
      margin: 15px 0;
    }

    #highlight {
      background-color: #ffff99; /* yellow highlight */
      padding: 15px;
      border: 2px solid #ff6347; /* tomato border */
      margin: 20px 0;
    }

    a {
      display: inline-block;
      margin: 10px 0;
      color: #ff1493; /* deep pink */
      text-decoration: none;
      font-weight: bold;
    }

    a:hover {
      color: #32cd32;
      text-decoration: underline;
    }

    hr {
      border: 1px solid #999;
      margin: 30px 0;
    }

    #first {
      font-size: 20px;
      color: #8b008b; /* dark magenta */
      background-color: #e6e6fa; /* lavender background */
      padding: 10px;
      border-radius: 5px;
    }
  </style>
</head>
<body>

  <h1>Hello Page, Hello Kids</h1>
  <hr>

  <h2 class="plaintext">Second Headline</h2>
  <p>This is more text, fun and colorful!</p>
  <hr>

  <div id="highlight">
    <h2>HI HIGHLIGHT</h2>
    <p>Look at this bright highlighted section!</p>
  </div>

  <a href="resource.html">GET RESOURCE!</a><br>
  <a href="#first">Scroll Down</a><br>
  <a href="resource.html#first">GET RESOURCE and scroll down!</a>

  <hr>
  <p id="first">This is the large text at the bottom. More style, more color, more fun!</p>

  <hr>
  <p>End of Page. Thank you for visiting! 🌟</p>

</body>
</html>
