<script>
  let { children } = $props();
</script>




<nav class="navbar navbar-expand-sm bg-body-tertiary">  
  <div class="container-fluid">
    <a class="navbar-brand" href="/#">
      DW4
    </a>
    <button
      class="navbar-toggler"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav">
        <li class="nav-item">
            <a class="nav-link" href="/Boletim">Conversor</a>
          </li>
      </ul>
    </div>
  </div>
</nav>


{@render children()}

<style>
  /* Alterando o fundo da barra de navegação */
  .navbar {
    font-family: 'Courier New', Courier, monospace;
    color: rgb(248, 0, 0);
    background-color: #000000; /* Escolha a cor desejada */
  }
</style>