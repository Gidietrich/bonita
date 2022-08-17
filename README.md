@import url('https://fonts.googleapis.com/css2?family=Bungee&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
}

body {
    font-size: 100%;
    background: linear-gradient(68.15deg, #2F2325 16.62%, #8E5D52 85.61%);
}

.cabecalho {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
    padding: 24px;
  }
  
  .cabecalho-imagem {
    height: 72px;
  }
  
  .cabecalho-menu {
    display: flex;
    gap: 32px;
  }
  
  .cabecalho-menu-item {
    font-family: 'Sarala', sans-serif;
    color: #FFF2E7;
    font-weight: 400;
    font-size: 18px
  }
  
  .conteudo {
    margin-bottom: 48px;
    border-top: 0.4px solid #FFF2E7;
  }
  
  .conteudo-principal {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
  }
  
  .conteudo-principal-escrito {
    display: flex;
    flex-direction: column;
    gap: 32px;
  }
  
  .conteudo-principal-escrito-titulo {
    font-family: 'Righteous', cursive;
    font-weight: 400;
    font-size: 64px;
    color: #FFF2E7;
  }
  
  .conteudo-principal-escrito-subtitulo {
    font-family: 'Sarala', sans-serif;
    font-weight: 400;
    font-size: 24px;
    color: #ECD6C4;
  }
  
  .conteudo-principal-escrito-botao {
    background-color: #ECD6C4;
    width: 180px;
    height: 60px;
    border: none;
    box-shadow: 4px 5px 4px rgba(0, 0, 0, 0.25);
    border-radius: 20px;
    font-family: 'Sarala', sans-serif;
    font-weight: 400;
    font-size: 24px;
    color: #2F2325;
  }
  
  .conteudo-principal-escrito-botao:hover {
    background-color: rgba(236, 214, 196, 0.53);
  }
  
  .conteudo-principal-imagem {
    height: 430px;
  }
  
  .conteudo-secundario {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 24px;
    margin-top: 48px;
  }
  
  .conteudo-secundario-titulo {
    border-top: 0.4px solid #FFF2E7;
    padding-top: 48px;
    font-family: 'Righteous', cursive;
    font-weight: 400;
    font-size: 24px;
    color: #FFF2EF;
    margin-bottom: 16px;
  }
  
  .conteudo-secundario-paragrafo {
    font-family: 'Sarala', sans-serif;
    font-weight: 300;
    font-size: 18px;
    color: #ECD6C4;
  }
  
  .rodape {
      padding: 32px;
      border-top: 0.4px solid #FFF2E7;
  }
  
  .rodape-imagem {
    height: 48px;
    display: block;
    margin: 0 auto;
