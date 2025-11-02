# javascript-practice1
Basic webpage using HTML and CSS with a centered navigation bar, hover effects, and welcome message — great for practicing flexbox and styling fundamentals.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
    nav{
        background-color: darkblue;
        display: flex;
        justify-content: center;
    }
    a {
        margin: 10px;
        color: white;
        text-decoration: none;
    }
    a:hover{
        background-color: orange;
        color: darkblue;
    }
    
    .welcome{
        background-color: green;
        margin-top: 10px;
    }
    .red{
        margin-top: 10px;
        color: red;
    }
  </style>
</head>
<body>
<body>

  <nav>
    <a href="#">HOME</a><a href="#">ACADEMICS</a><a href="#">ADMISSIONS</a><a href="#">RESEARCH</a><a href="#">CONTACT</a>
  </nav>

  <div class="welcome">
    <b>Welcome to Lovely Professional University</b>
  </div>

  <div class="red">
    To manage the university task and to give information about university.
  </div>


</body>
</html>
