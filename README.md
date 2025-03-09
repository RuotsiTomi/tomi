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
        }
        .title {
            font-size: 3rem;
            font-weight: bold;
            text-shadow: 0px 0px 10px rgba(0,255,255,0.8);
        }
        .profile-img {
            width: 200px;
            border-radius: 50%;
            margin-top: 20px;
        }
        .content {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 10px;
            display: none;
        }
        h2 {
            color: cyan;
            cursor: pointer;
        }
        .nav {
            background: rgba(0, 0, 0, 0.8);
            padding: 10px 0;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
        }
        .nav a {
            color: cyan;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            cursor: pointer;
        }
        .nav a:hover {
            text-decoration: underline;
        }
    </style>
    <script>
        function toggleContent(id) {
            var content = document.getElementById(id);
            if (content.style.display === "none" || content.style.display === "") {
                content.style.display = "block";
            } else {
                content.style.display = "none";
            }
        }
    </script>
</head>
<body>
    <div class="nav">
        <a onclick="toggleContent('osaaminen')">Osaaminen</a>
        <a onclick="toggleContent('sijoittaminen')">Sijoittaminen</a>
        <a onclick="toggleContent('3d-tulostus')">3D-tulostus</a>
        <a onclick="toggleContent('portfolio')">Portfolio</a>
    </div>
    
    <div class="container">
        <img src="logo.webp" alt="Portfolio Logo" class="logo">
        <h1 class="title">Tervetuloa Portfoliooni</h1>
        <img src="omakuva.jpg" alt="Profiilikuva" class="profile-img">
    </div>
    
    <div class="content" id="osaaminen">
        <h2 onclick="toggleContent('osaaminen')">Osaaminen ja Kokemus</h2>
        <p>Toimin teknisenä asiantuntijana Danfoss Leanhetillä ulkoisena työntekijänä Academic Workin kautta. Työtehtäviini kuuluu tekninen tuki isännöinnille, huollolle ja asentajille, uusien kohteiden luominen sekä erilaiset integraatiot.</p>
        <p>Kouluttaudun talotekniikan insinööriksi ja minulla on koulu hyvin jo voiton puolella., Minulla on 11 vuoden kokemus asennustöistä, sekä 8 kuukautta kokemusta teknisenä asiantuntijana, joten suurinosa osaamisestani talotekniiikan saralla ei ole tullut koulusta, vain suoraan kentältä. Asentaja toimin hyvin monipuolisissa tehtävissä ja siitä kertoo esim kaasu- öljy- ja S3R sähköpätevyydet. </p>
    </div>
    
    <div class="content" id="sijoittaminen">
        <h2 onclick="toggleContent('sijoittaminen')">Sijoittaminen ja Koodaus</h2>
        <p>Olen kiinnostunut vaurastumisesta ja sijoittamisesta, erityisesti korkeariskisistä sijoituksista ja isoista tuotoista. Tavoitteeni on olla taloudellisesti riippumaton, kun täytän 40 vuotta. Keskityn sekä pitkäaikaiseen kryptosijoittamiseen, että arvosijoittamiseen. Näen sijoittamisessa suurimpana hyötynä laajan hajauttamisen. Olen myös toiminut asuntosijoittana noin 10 vuotta ja sitä kautta oppinut useita tärkeitä taitoja, niin yleisesti elämiseen, kun sijoittamiseen. </p>
        <p>Pidän koodauksesta ja mallintamisesta ja olen käyttänyt GitHubia omiin projekteihini. Olen kuitenkin tämän saralla vielä oman osaamiseni alkutaipaleella, mutta omaan ajatusmaailmaani sopii parjaiten, että tekemällä oppii. </p>
    </div>
    
    <div class="content" id="3d-tulostus">
        <h2 onclick="toggleContent('3d-tulostus')">3D-tulostus</h2>
        <p>Omistan 3D-tulostimen ja olen erittäin kiinnostunut mallintamisesta. Olen muutamia prototyyppejä mallintanut arjessa tulleisiin tarpeisiin.</p>
    </div>
    
    <div class="content" id="portfolio">
        <h2 onclick="toggleContent('portfolio')">Portfolio</h2>
        <p>Toivon, että tämä sivusto avasi osaamistani ja kiinnostuksen kohteitani enemmän.</p>
        <p>Minut tavoittaa sähköpostista tomi_r@hotmail.com
    </div>
</body>
</html>
