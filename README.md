<!DOCTYPE html>
<html lang="fi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - TR</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background: url('background.webp') no-repeat center center fixed;
            background-size: cover;
            color: white;
            text-align: center;
        }
        .logo {
            width: 150px;
            margin: 20px;
        }
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            backdrop-filter: blur(5px);
            padding: 20px;
        }
        .title {
            font-size: 2.5rem;
            font-weight: bold;
            text-shadow: 0px 0px 10px rgba(0,255,255,0.8);
        }
        .profile-img {
            width: 150px;
            border-radius: 50%;
            margin-top: 20px;
        }
        .nav {
            background: rgba(0, 0, 0, 0.8);
            padding: 10px 0;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            display: flex;
            justify-content: center;
        }
        .nav a {
            color: cyan;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .nav a:hover {
            text-decoration: underline;
        }
        @media (max-width: 768px) {
            .title {
                font-size: 2rem;
            }
            .profile-img {
                width: 120px;
            }
            .nav a {
                margin: 0 10px;
                font-size: 14px;
            }
        }
    </style>
</head>
<body>
    <div class="nav">
        <a href="osaaminen.html">Osaaminen</a>
        <a href="sijoittaminen.html">Sijoittaminen</a>
        <a href="3d-tulostus.html">3D-tulostus</a>
        <a href="portfolio.html">Portfolio</a>
    </div>
    
    <div class="container">
        <img src="logo.webp" alt="Portfolio Logo" class="logo">
        <h1 class="title">Tervetuloa Portfoliooni</h1>
        <img src="omakuva.jpg" alt="Profiilikuva" class="profile-img">
    </div>
</body>
</html>
