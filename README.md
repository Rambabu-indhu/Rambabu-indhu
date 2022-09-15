 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>I DACE STUDIO ORGANISER MR VASU</title>
    <style>
        body{
            padding: 0px;
            margin: 0px;
            box-sizing: border-box;
            background-color: cyan;
        }
        .container{
            height: 100vh;
            margin: 0px;
            padding: 0px;
        }
        .logo{
            margin-left: 50px;
            font-size: 18px;
            animation: logo 2s infinite;
            transition: all ease;
        }
        @keyframes logo {
            0%{
                color: blue;
            }
            25%{
                color: orange;
            }
            50%{
                color: lavender;
            }
            75%{
                color:greenyellow;
            }
            100%{
                color: white;
            }
        }
        header{
            background-color: rgba(0, 0, 0, 0.574);
            padding: 5px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: fixed;
            width: 100%;
        }
        ul{
          position:relative;
            float: left;
            list-style: none;
            margin-right: 10px; 
        }
        ul li{
            display: inline-block;
            width: 90px;
            text-align: center;
            padding: 5px 10px;
            border-width: 0px;
            border: 2px solid transparent; 
        }
        ul li:hover{
            border: 2px solid white;
            border-radius: 8px;
        }
        ul li a{
            color: white;
            font-size: 18px;
            text-decoration: none;
        }
        @media(max-width: 395px) {
  .navbar{
    position: absolute;
   
 
    top: 100%;
    left: 25%;
   
    
  }
}
        
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">
                <h1>I DACE STUDIO</h1>
            </div>
            <div class="navbar">
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Contact Us</a></li>
                    <li><a href="#">Help</a></li>
                    <li><a href="#">Location</a></li>
                </ul>
            </div>
        </header>
    </div>
</body>
</html
