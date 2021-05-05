# Gym-fitnees-simple-home--website
  code is in CSS+HTML5
          <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>brd Fitness</title>
    <link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Girassol&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <style>
        body{ color: white;
            margin: 0px;
            padding: 0px;
           background: url('gym\ photo.jpg');
           font-family: girassol;
    
        }
        .left{
            display: inline-block;
           /* border: 2px solid #8a2be2; */
           position: absolute;
            left: 34px;
            top: 20px;
        }
        .left img{
            width: 130px;
            filter: invert(0);

        }
        .mid{
            display: block;
            width: 40%;
            top: 20px;
            margin:  12px auto;
            /* border: 2px solid rgb(238, 130, 238); */
        }
        .right{
            position: absolute;
            right: 34px;
            top: 20px;
            display: inline-block;
            /* border: 2px solid rgb(221, 160, 221); */
        } .navbar{
            display: inline-block;
        } .navbar li{
            
            display: inline-block;
            font-size: 21px;
        } .navbar li a{
            color: white;
            text-decoration: none;
            padding: 34px 24px;
        }
        .navbar li a:hover , .navbar li a.active{
            text-decoration: underline;
            color: rgb(46, 206, 228);
        }.btn{
            font-family: girassol;
            margin: 0px 9px;
            color: black;
            background-color: white;
            padding: 7px 7px;
            /* border: 2px solid rgb(20, 175, 223); */
            border-radius: 10px;
            font-size: 12px;
            cursor: pointer;
        } .btn:hover{
            background-color: #D8BFD8;
        } .container{
            /* border: 2px solid #CCCCFF; */
            margin: 100px 30px;
            padding: 50px ;
            width: 33%;
            border-radius: 20px;
            text-align: center;
        }
        .form-group input{
               text-align: center;
               display: block;
               width: 300px;
               padding: 5px;
               /* border: 2px solid black; */
               margin: 2px auto;
               font-size: 15px;
               border-radius: 20px;
               font-family: girassol;
               cursor: pointer;
        }

    </style>
</head>
<body>
    <header class="header">
        <!-- left box for logo -->
        <div class ="left">
            <img src="gym logo.jpg" alt="">
            <div style="text-align: center;">BRD Fitness</div>
        </div>
        <!-- mid for navbar -->
        <div class="mid">
            <ul class="navbar">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">About us</a></li>
                <li><a href="#">Fitness Calculator</a></li>
                <li><a href="#">Contact us</a></li>
            </ul>
        </div>
          <!-- right box for button -->
        <div class="right">
    <button class="btn">Call us now</button><button class="btn">Email us</button>
        </div>
    </header>
    <div class="container">
        <h1> Join the best gym of Ghatal now</h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Name ">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder=" Enter your Age">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Gender">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Locality">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Contact Number">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Email Id">
            </div>
            <button class="btn" style="padding: 10px 50px;">Submit</button>
        </form>
    </div>
</body>
</html>
/* made by brdcoder 007 */
