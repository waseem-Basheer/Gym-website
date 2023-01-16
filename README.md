<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Document</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat:wght@900&family=Ubuntu&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="css/styles.css" />
    <style>
      body {
        color: white;
        font-family: "Ubuntu", sans-serif;
        margin: 0;
        padding: 0;
        background: url("images/s.jpg");
      }
      .left {
        display: inline-block;

        position: absolute;
        top: 20px;
        left: 34px;
      }
      .left img {
        width: 100px;
      }
      .left div {
        text-align: center;
      }
      .mid {
        display: block;
        width: 33%;
        margin: 24px auto;
      }
      .right {
        position: absolute;
        right: 34px;
        top: 20px;
        display: inline-block;
      }
      .navbar {
        display: inline-block;
      }
      .navbar li {
        display: inline-block;
        font-size: 17px;
      }
      .navbar li a {
        color: white;
        text-decoration: none;
        padding: 12px 13px;
      }
      .navbar li a:hover {
        color: grey;
      }
      .btn {
        padding: 4px 14px;
        margin: 0 9px;
        background-color: black;
        color: white;
        border: 2px solid gray;
        border-radius: 5px;
        cursor: pointer;
      }
      .btn:hover {
        background-color: gray;
      }
      .container {
        margin: 106px 80px;
        padding: 75px;
        width: 31%;
        border-radius: 23px;
        text-align: center;
      }
      .container button {
        display: block;
        padding: 4px 14px;
        width: 23%;
        margin: auto;
        color: white;
        border-radius: 3px;
        border: 2px solid;
        background-color: black;
      }
      .container button:hover {
        background-color: gray;
      }
      .form-group input {
        text-align: center;
        display: block;
        width: 250px;
        padding: 1px;
        margin: 11px auto;
        font-size: 15px;
        border-radius: 12px;
        font-family: "Ubuntu", sans-serif;
      }
    </style>
  </head>
  <body>
    <header class="header">
      <div class="left">
        <img src="images/i.jpg" alt="" />
        <div>Fitness Club</div>
      </div>

      <div class="mid">
        <ul class="navbar">
          <li><a href="#" class="active">Home</a></li>
          <li><a href="#">Fitness Calculator</a></li>
          <li><a href="#">Contact Us</a></li>
          <li><a href="#">About Us</a></li>
        </ul>
      </div>
      <div class="right">
        <button class="btn">Call Us</button><button class="btn">Join Us</button>
      </div>
    </header>
    <div class="container">
      <h1>Join The Best Gym Of Srinagar</h1>
      <form action="noaction.php">
        <div class="form-group">
          <input type="text" placeholder="Enter Your name" />
        </div>
        <div class="form-group">
          <input type="text" placeholder="Enter Your Age" />
        </div>
        <div class="form-group">
          <input type="text" placeholder="Enter Your Gendre" />
        </div>
        <button class="button">Submit</button>
      </form>
    </div>
  </body>
</html>
