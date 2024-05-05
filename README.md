# Desafio Dio - Recriando a página inicial do Instagram

Esse é o repositório da nossa aula de Flexbox, na qual vamos fazer a interface de login do Instagram! 

## Os requisitos são:

* [HTML básico](https://www.w3schools.com/html/)
* [CSS básico](https://developer.mozilla.org/pt-BR/docs/Web/CSS)

##  Let's code! 

O projeto de recriação da página inicial do Instagram consiste em reproduzir a página inicial da plataforma de mídia social, utilizando o conceito de CSS utilizando Flexbox. O projeto visa proporcionar a compreensão dos fundamentos de CSS com Flexbox, além de estimular o desenvolvimento de projetos de layout responsivo.

O projeto pode ser realizado utilizando a plataforma CodePen, onde o código pode ser desenvolvido e compartilhado com outros desenvolvedores.

A seguir, são descritos os passos para a realização do projeto:

1. Acesse a página inicial do Instagram e identifique os elementos que compõem o layout da página.
2. Abra o CodePen e crie um novo projeto.
3. Crie uma nova classe para cada elemento do layout da página.
4. Adicione os estilos CSS aos elementos da página.
5. Defina os valores de propriedade flex para cada elemento da página.
6. Teste o projeto e verifique se o layout está correto.

Após a conclusão do projeto, você deve ter uma boa compreensão dos fundamentos de CSS com Flexbox, além de ter desenvolvido um projeto de layout responsivo.

A seguir, é apresentado um exemplo de código para a recriação da página inicial do Instagram:



<!DOCTYPE html> <html>   <head>     <meta charset="UTF-8">     <meta name="viewport" content="width=device-width, initial-scale=1.0">     <title>Recriação da página inicial do Instagram</title>     <link rel="stylesheet" href="style.css">   </head>   <body>     <div class="header">       <img src="logo.png" alt="Logo do Instagram">       <input type="text" placeholder="Buscar...">       <button>         <svg viewBox="0 0 24 24">           <path d="M12 12c2.21 0 4 1.79 4 4s-1.79 4-4 4-4-1.79-4-4 1.79-4 4-4zm0 2c-1.1 0-2 .9-2 2s1 2 2 2 2-.9 2-2-.9-2-2-2zm0 10c-1.66 0-3.11-.85-4-2s-.89-3.33-2-4 .89-3.11 2-4 3.11-2 4-2zm0-4c-.55 0-1-.45-1-1s.45-1 1-1 1 .45 1 1-.45 1-1 1z"/>         </svg>       </button>     </div>     <div class="main">       <ul class="feed">         <li>           <img src="image1.jpg" alt="Imagem 1">           <div class="description">             <h2>Nome do usuário</h2>             <p>Descrição da imagem</p>           </div>         </li>         <li>           <img src="image2.jpg" alt="Imagem 2">           <div class="description">             <h2>Nome do usuário</h2>             <p>Descrição da imagem</p>           </div>         </li>         <li>           <img src="image3.jpg" alt="Imagem 3">           <div class="description">             <h2>Nome do usuário</h2>             <p>Descrição da imagem</p>           </div>         </li>         <li>           <img src="image4.jpg" alt="Imagem 4">           <div class="description">             <h2>Nome do usuário</h2>             <p>Descrição da imagem</p>           </div>         </li>       </ul>     </div>     <div class="footer">       <ul>         <li><a href="#">Sobre</a></li>         <li><a href="#">Ajuda</a></li>         <li><a href="#">Termos de uso</a></li>         <li><a href="#">Política de privacidade</a></li>       </ul>     

