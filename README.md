# exe1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML - PAGE</title>
    <style>
         .planet{
             height: "250px"; 
             width: "250px";
         }
         .menu{
            display: inline;
            padding: 12px 16px;
         }
         .section{
            width: 100%;
            height: 550px;
         }
         #topbar{
            list-style-type: none;
            background-color: lightpink;
         }
         #fist_section{
            background-color: lightblue;
         }
         #second_section{
            background-color: lightcyan;
         }
         #third_section{
            background-color: lightgray;
         }
    </style>
</head>
<body>
    
<ul id="topbar">
    <li class="menu"><a href="/index.html#fist_section"> HOME </a></li>
    <li class="menu"><a href="/index.html#second_section"> About </a></li>
    <li class="menu"><a href="/index.html#third_section"> contact </a></li>
</ul>
<div id="fist_section" class="section">
    <h1>Landing Section </h1>
</div>
<div id="second_section" class="section">
    <h1>About Section</h1>
</div>
<div id="third_section" class="section">
    <h1>contact section</h1>
</div>
</body> 
</html>
