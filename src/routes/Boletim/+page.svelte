<script>
  // svelte-ignore non_reactive_update
    let np, nt, ns;
  let nf = $state();

  function calcularnota() {
    nf = (np * 5 + ns * 3 + nt * 2) / 10;
  }
</script>

<head>
  <style>
    body {
      background-image: url('IMG-20240821-WA0006.jpg'); 
      background-size: cover; 
      background-position: center;
      background-attachment: fixed; 
      font-family: 'Times New Roman', Times, serif;
    }
  </style>
</head>

<h1>Boletim Escolar</h1>

Nota da prova:
<input type="number" min="0" max="10" bind:value={np} />
<br />

Nota do trabalho:
<input type="number" min="0" max="10" bind:value={nt} />
<br />

Nota do seminário:
<input type="number" min="0" max="10" bind:value={ns} />
<br />

<button onclick={calcularnota}> Calcular a nota final!</button>

<p>Tua nota final é: {nf || '...'}</p>

{#if nf >= 8.5}
  <p>Conceito A, aprovado 😁</p>
{:else if nf >= 7}
  <p>Conceito B, aprovado 😎</p>
{:else if nf >= 5}
  <p>Conceito C, recuperação 😅</p>
{:else if nf >= 2.5}
  <p>Conceito D, recuperação 😣</p>
{:else if nf}
  <p>Conceito E, reprovado 😱</p>
{/if}
