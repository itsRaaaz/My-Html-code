# My-Html-code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Iphone</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" />
    <style>
        *{
            margin: 0;
            padding: 0;
        }
        main{
            height: 699px;
            width: 368px;
            margin: 5px;
            border: 5px solid rgb(240, 181, 191);
            border-radius: 54px;
            border-style: groove;
            position: absolute;
        }
        section{
            height: 670px;
            width: 340px;
            background-image: url("wallpaper.jpg");
            border: 15px solid black;
            border-radius: 50px;

        }
        nav{
            height: 30px;
            width: 100%;
            display: flex;
            margin-top: 07px;
        }
        #iland{
            height: 30px;
            width: 140px;
            background-color: black;
            margin-left: 98px;
            
            border-radius: 70px;
            
        }
        #bar{
            height: 5px;
            width: 200px;
            background-color: rgb(246, 244, 244);
            margin-top: 20px;
            margin-left: 70px;
            border-radius: 7px;
        }
        #icon{
            color: aliceblue;
            margin-top: 6px;
            margin-left: 10px;
        }
        #icon i{
            margin-left: 5px;
        }
        #date{
            height: 30px;
            width: 100%;
            margin-top: 30px;
            text-align: center;
            font-size: 20px;
            font-weight: 550;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color: white;
        }
        #time{
            height: 60px;
            width: 100%;
            font-size: 60px;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            font-weight: 600;
            margin-left: 110px;
            color: white;
        }
        footer{
            margin-top: 420px;
            display: flex;
            
        }
        #torch{
            margin-left: 20px;
            
        }
        #torch img{
            border: 1px solid black;
            border-style: transparent;
            border-radius: 100px;
        }
        #text{
            color: white;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            margin-left: 20px;
            margin-top: 35px;
            
            
        }
        #camera{
            margin-left: 20px;
        }
        #camera img{
            border: 1px solid black;
            border-style: transparent;
            border-radius: 100px;

        }

    </style>
</head>
<body>
    <main>
        <section>
        <nav id="nav">
            <div id="iland">

            </div>
            <div id="icon">
                <i class="fa-solid fa-signal"></i>
                <i class="fa-solid fa-wifi"></i>
                <i class="fa-solid fa-battery-half"></i>

            </div>
        </nav>
        <div id="date">
            <p>Monday, June 5</p>
        </div>
        <div id="time">
            <p>9:41</p>

        </div>
        <footer>
            <span id="torch">
                <img src="torch.png" height="50" width="50">
            </span>
            <span id="text">
                <p>Swipe up to unlock</p>
            </span>
            <span id="camera">
                <img src="camera.png" height="50px" width="50">
            </span>
        </footer>

            <div id="bar">

            </div>

        </section>

    </main>

    
</body>
</html>
