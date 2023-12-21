# codigos-HTML-E-CSS
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercicio de CSS</title>
    <link rel="stylesheet" type="text/css" href="estilo.css">
</head>
<body>
    <header>
        <h1 class="cabeçalho">Bem-vindo ao Meu Site</h1>
        </header>
        <nav>
        <ul>
        <li><a href="#">Início</a></li> 
        
        <li><a href= "#">Sobre</a></li> 
        
        <li><a href="#">Contato</a></li> 
        
        </ul>
        </nav>
        <section>
        <article>
        <h2>Artigo 1</h2>
        <p>Este é o primeiro artigo.</p>
        </article>
        <article>
        <h2>Artigo 2</h2>
        <p>Este é o segundo artigo.</p>
        </article>
        </section>
        <footer>
        <p>Direitos autorais © 2023</p>
        </footer>
</body>
</html>
______________________________________________________________________
CSS 

.cabeçalho{
    text-align: center;
}
body{
    background-image: url(https://img.freepik.com/vetores-gratis/fundo-do-dia-mundial-da-arte-em-aquarela_23-2149327049.jpg?w=2000);
}
header {
    background-color:rgb(219, 219, 219)
    }
    
    ul {
    list-style-type: none;
    padding: 0; /*Espaço interno*/
    }
    
    li {
    display: inline; /*desbloqueia espaços ao lado*/
    margin-right: 10px;
    }
    
    article {
    border: 1px solid black; /*borda solida ou pontilhada ou trassejada*/
    margin: 10px; /*espaço externo*/
    }
    
    footer {
    background-color: darkgray;
    color: white;
    text-align: center;
    }
