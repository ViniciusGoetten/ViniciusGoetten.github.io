<style>
    :global(html) {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        background: url('teste.jpg') no-repeat center center fixed;
        background-size: cover;
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

    /* Fundo para os vilões */
    .background-viloes {
        background: url('teste.jpg') no-repeat center center;
        background-size: cover;
        padding: 50px 0;
    }

    /* Vilões */
    .team-gallery {
        display: grid;
        grid-template-columns: repeat(4, 1fr);
        gap: 20px;
        justify-items: center;
        padding: 40px;
    }

    .team-card {
        width: 250px;
        background-color: rgba(255, 255, 255, 0.8);
        border-radius: 15px;
        box-shadow: 0 10px 30px rgba(0, 0, 0, 0.05);
        padding: 15px;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
        overflow: hidden;
    }

    .team-card img {
        width: 100%;
        height: 300px;
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
</style>

<nav>
    <div class="logo-container">
        <img src="teste.jpg" alt="Dexter" class="logo">
        <span style="color: white; font-size: 1.7em; font-weight: bold;">Dexter</span>
    </div>
    <ul>
        <li><a href="Episódios">Episódios</a></li>
        <li><a href="Descrições">Descrições</a></li>
        <li><a href="https://www.imdb.com/pt/title/tt0773262/?ref_=nv_sr_srsg_0_tt_2_nm_6_q_dexter" target="_blank">Imdb</a></li>
        <li><a href="Notícias">Notícias</a></li>
    </ul>
</nav>

<!-- Vilões -->
<div class="background-viloes">
    <div class="container">
        <div class="section-title">Vilões de Dexter</div>
        <div class="team-gallery">
            <div class="team-card">
                <img src="BrianMoser.webp" alt="Brian Moser">
                <h3>Brian Moser</h3>
            </div>
            <div class="team-card">
                <img src="avatarhd.avif" alt="Lila West">
                <h3>Lila West</h3>
            </div>
            <div class="team-card">
                <img src="Miguel_Prado.webp" alt="Miguel Prado">
                <h3>Miguel Prado</h3>
            </div>
            <div class="team-card">
                <img src="trinity.jpg" alt="Trinity">
                <h3>Trinity</h3>
            </div>
            <div class="team-card">
                <img src="from-jordan-chase-to-sherlock-holmes-this-dude-is-an-v0-209vqmu72m2d1.webp" alt="Jordan Chase">
                <h3>Jordan Chase</h3>
            </div>
            <div class="team-card">
                <img src="TravisM.webp" alt="Travis Marshall">
                <h3>Travis Marshall</h3>
            </div>
            <div class="team-card">
                <img src="Isaak_Sirko_Dexter.webp" alt="Isaak Sirko">
                <h3>Isaak Sirko</h3>
            </div>
            <div class="team-card">
                <img src="Oliver_Saxon.webp" alt="Oliver Saxon">
                <h3>Oliver Saxon</h3>
            </div>
        </div>
    </div>
</div>