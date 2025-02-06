<script>
    let noticias = [
        {
            titulo: "Dexter Retorna com Nova Temporada",
            descricao: "Após anos de espera, a série *Dexter* voltou com uma nova temporada intitulada *Dexter: New Blood*.",
            link: "https://www.rollingstone.com/tv-movies/tv-movie-reviews/dexter-new-blood-review-1254733/"
        },
        {
            titulo: "Os Vilões Mais Icônicos de Dexter",
            descricao: "Uma análise dos antagonistas mais memoráveis da série, incluindo Trinity Killer e Ice Truck Killer.",
            link: "https://screenrant.com/dexter-best-villains-ranked/"
        },
        {
            titulo: "Final Polêmico de Dexter Divide Fãs",
            descricao: "O desfecho da série original gerou grande debate entre os fãs, dividindo opiniões.",
            link: "https://www.indiewire.com/2013/09/why-the-dexter-series-finale-was-so-disappointing-165383/"
        }
    ];
</script>

<div class="container">
    <h1>Últimas Notícias sobre Dexter</h1>
    {#each noticias as noticia}
        <div class="news-item">
            <h3>{noticia.titulo}</h3>
            <p>{noticia.descricao}</p>
            <a href={noticia.link} target="_blank">Leia mais</a>
        </div>
    {/each}
</div>

<style>
    .container {
        max-width: 800px;
        margin: auto;
        background: white;
        padding: 20px;
        border-radius: 8px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    h1 {
        text-align: center;
    }
    .news-item {
        border-bottom: 1px solid #ccc;
        padding: 10px 0;
    }
    .news-item:last-child {
        border-bottom: none;
    }
    a {
        text-decoration: none;
        color: #007BFF;
    }
</style>