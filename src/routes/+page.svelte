<title>Início - Dexter</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            text-align: center;
            color: #333;
        }

        /* Barra de navegação */
        nav {
            background-color: #2e0202;
            width: 100%;
            padding: 15px 0;
            position: fixed;
            top: 0;
            left: 0;
            z-index: 100;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        nav .logo-container {
            display: flex;
            align-items: center;
            margin-left: 20px;
        }

        nav .logo {
            height: 50px;
            width: auto;
            margin-right: 10px;
        }

        nav ul {
            list-style-type: none;
            display: flex;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            margin: 0 25px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 1.2em;
            text-transform: uppercase;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: #0061F2;
        }

        /* Seção Hero */
        .hero-section {
            background-color: #8f0000;
            color: white;
            padding: 120px 20px;
            text-align: center;
            font-size: 2.5em;
            font-weight: bold;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        /* Vilões */
        .team-gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 60px;
            gap: 20px;
            padding: 0 20px;
        }

        .team-card {
            width: 230px;
            background-color: #ffffff;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.05);
            padding: 15px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            overflow: hidden;
        }

        .team-card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }

        .team-card h3 {
            margin-top: 15px;
            font-size: 1.6em;
            color: #003A5C;
            font-weight: bold;
        }

        .team-card:hover {
            transform: scale(1.05);
            box-shadow: 0 15px 45px rgba(0, 0, 0, 0.15);
        }

        .team-card:hover img {
            transform: scale(1.1);
        }

        
      
        .section-link:hover {
            background-color: #0061F2;
            color: white;
        }

        /* Layout do conteúdo */
        .container {
            margin-top: 160px;
            padding: 20px;
        }

        .container .section-title {
            font-size: 2.5em;
            color: #960202;
            margin-bottom: 30px;
            font-weight: bold;
        }
    </style>


    <nav>
        <div class="logo-container">
            <img src="teste.jpg" alt="UEFA Champions League" class="logo">
            <span style="color: white; font-size: 1.7em; font-weight: bold;">UEFA Champions League</span>
        </div>
        <ul>
            <li><a href="Eps">Melhores Episódios</a></li>
            <li><a href="Descrições">Descrições</a></li>
            <li><a href="Imdb">Imdb</a></li>
            <li><a href="Notícias">Notícias</a></li>
        </ul>
    </nav>


    <!-- Vilões -->
    <div class="container">
        <div class="section-title">Vilões de Dexter</div>
        <div class="team-gallery">
            <div class="team-card">
                <img src="BrianMoser.webp" alt="Liverpool">
                <h3>Brian Moser</h3>
            </div>
            <div class="team-card">
                <img src="https://upload.wikimedia.org/wikipedia/commons/4/47/FC_Barcelona_%28logo%29.svg" alt="Barcelona">
                <h3>Lila West</h3>
            </div>
            <div class="team-card">
                <img src="https://upload.wikimedia.org/wikipedia/commons/0/0e/Atletico_Madrid_logo.svg" alt="Atlético de Madrid">
                <h3>Miguel Prado</h3>
            </div>
            <div class="team-card">
                <img src="https://upload.wikimedia.org/wikipedia/commons/4/45/Arsenal_FC.svg" alt="Arsenal">
                <h3>Trinity</h3>
            </div>
            <div class="team-card">
                <img src="https://upload.wikimedia.org/wikipedia/commons/e/ea/Logo_Bayer_04_Leverkusen.svg" alt="Bayer Leverkusen">
                <h3>Jordan Chase</h3>
            </div>
            <div class="team-card">
                <img src="https://upload.wikimedia.org/wikipedia/commons/d/d2/FC_Internazionale_Milano_logo.svg" alt="Internazionale">
                <h3>Travis Marshall</h3>
            <div class="team-card">
                <img src="https://upload.wikimedia.org/wikipedia/commons/d/d2/FC_Internazionale_Milano_logo.svg" alt="Internazionale">
                <h3>Isaak Sirko</h3>
            <div class="team-card">
                <img src="https://upload.wikimedia.org/wikipedia/commons/d/d2/FC_Internazionale_Milano_logo.svg" alt="Internazionale">
                <h3>Oliver Saxon</h3>
            </div>
        </div>
    </div>