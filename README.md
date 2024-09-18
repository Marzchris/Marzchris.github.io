<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout</title>
    <link rel="stylesheet" type="text/css" href="css/960_12_col.css">
    <style>
        @font-face {
            font-family: 'QuicksandBook';
            src: url('fonts/Quicksand_Book-webfont.eot');
            src: url('fonts/Quicksand_Book-webfont.eot?#iefix') format('embedded-opentype'),
                 url('fonts/Quicksand_Book-webfont.woff') format('woff'),
                 url('fonts/Quicksand_Book-webfont.ttf') format('truetype'),
                 url('fonts/Quicksand_Book-webfont.svg#QuicksandBook') format('svg');
            font-weight: normal;
            font-style: normal;
        }

        body {
            color: #ffffff;
            background: #413f3b url("images/ug.jpg");
            font-family: Georgia, "Times New Roman", Times, serif;
            font-size: 90%;
            margin: 0px;
            text-align: center;
        }

        a {
            color: #b5c1ad;
            text-decoration: none;
        }

        a:hover {
            color: #ffffff;
        }

        .header {
            background-image: url("images/bg-header.jpg");
            padding: 0;
            height: 100px;
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 50;
        }

        .nav {
            float: right;
            font-family: QuicksandBook, Helvetica, Arial, sans-serif;
            padding: 45px 0 0;
            text-align: right;
        }

        .wrapper {
            width: 960px;
            margin: 0 auto;
            background-image: url("images/bg-triangle.png");
            background-position: 0 0;
            text-align: left;
        }

        h1, h2 {
            font-family: QuicksandBook, Helvetica, Arial, sans-serif;
            font-weight: normal;
            text-transform: uppercase;
        }

        h1 {
            font-size: 240%;
            margin-top: 140px;
        }

        .date {
            font-family: Arial, Helvetica, sans-serif;
            font-size: 75%;
            color: #b5c1ad;
        }

        .intro {
            clear: left;
            font-size: 90%;
            line-height: 1.4;
        }

        .main-story {
            background-image: url("images/triangles.png");
            background-repeat: no-repeat;
            background-position: 122px 142px;
            height: 570px;
        }

        .more-articles {
            border-top: 1px solid #ffffff;
            padding: 10px;
        }

        .more-articles p {
            border-bottom: 1px solid #807c72;
            padding: 5px 0 15px;
            font-size: 80%;
        }

        .more-articles p:last-child {
            border-bottom: none;
        }

        .footer {
            clear: both;
            background: rgba(0, 0, 0, 0.2);
            padding: 5px 10px;
        }

        .footer p {
            font-family: Helvetica, Arial, sans-serif;
            font-size: 75%;
            text-align: right;
        }

        .footer a {
            color: #807c72;
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="container_12">
            <div class="grid_5">
                <img src="images/logo.png" alt="Pedal Faster - The modern bicycle magazine" width="216" height="37" class="logo">
                <img src="images/header-triangle.png" alt="" width="116" height="100">
            </div>
            <div class="nav grid_7">
                <a href="#">Home</a> / 
                <a href="#">News</a> / 
                <a href="#">Archives</a> / 
                <a href="#">About</a> / 
                <a href="#">Contact</a>
            </div>
        </div>
    </div>

    <div class="wrapper">
        <div class="main-story container_12">
            <div class="grid_6 push_6">
                <h1><a href="#">Fixed Gear Forever</a></h1>
            </div>
            <div class="intro grid_3 push_9">
                <p class="date">16 APRIL 2011</p>
                <p>The veloheld combines minimalist design with superb quality. Devoid of excessive graphics and gear shift components, the veloheld product range delights us with its beauty and simplicity ...</p>
            </div>
        </div>

        <div class="more-articles container_12">
            <h2 class="grid_12"><a href="#">More Articles</a></h2>
            <div class="grid_3">
                <img src="images/more1.jpg" alt="The road ahead" width="220" height="125">
                <p><a href="#">On the Road: From the fixed gear fanatic's point of view</a></p>
                <p><a href="#">Brand History: Pashley Cycles - hand-built in England</a></p>
                <p><a href="#">Frame Wars: Innovations in cycle manufacture and repair</a></p>
            </div>

            <!-- Additional article grids can go here -->

        </div>
    </div>

    <div class="footer clearfix">
        <div class="container_12">
            <p class="grid_12">
                <a href="#">Legal Information</a> | 
                <a href="#">Privacy Policy</a> | 
                <a href="#">Copyright &copy; Pedal Faster 2011</a>
            </p>
        </div>
    </div>
</body>
</html>

