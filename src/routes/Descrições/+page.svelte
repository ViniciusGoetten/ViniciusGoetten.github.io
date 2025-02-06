<script>
    let historia = `Dexter Morgan é um especialista forense em análise de padrões de sangue para o Departamento de Polícia de Miami. No entanto, por trás de sua fachada de homem comum, ele é um serial killer que segue um rígido código de conduta ensinado por seu pai adotivo, Harry. O "Código de Harry" estabelece que Dexter só pode matar outros assassinos que escaparam da justiça. 
    
    Ao longo da série, Dexter lida com sua natureza dupla, equilibrando sua vida como pai, irmão e policial com sua compulsão por matar. Sua jornada é marcada por desafios emocionais, investigações perigosas e confrontos com outros assassinos, incluindo seu próprio irmão biológico e figuras como o Trinity Killer.`;
  </script>
  
  <main class="historia-container">
    <h1>História de Dexter</h1>
    <img src="photo.avif" alt="Dexter Logo" class="dexter-img" />
    <p>{historia}</p>
  </main>
  
  <style>
    .historia-container {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
      text-align: center;
    }
  
    .historia-container h1 {
      color: #8b0000;
      font-size: 2rem;
    }
  
    .dexter-img {
      width: 100%;
      max-width: 400px;
      border-radius: 10px;
      margin: 20px 0;
    }
  
    .historia-container p {
      font-size: 1.1rem;
      line-height: 1.6;
      color: #333;
    }
  </style>