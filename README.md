<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="style.css"> 
  <link rel="stylesheet" href="procedimentos.css">
  <link rel="shortcut icon" href="imagens/favicon.ico" type="image/x-icon" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;700&display=swap" rel="stylesheet">

  <title>Estetica avançada</title>
  
</head>

<body>  
   <div class="numero">
     <a href="https://api.whatsapp.com/send?phone=558296626789&text=Texto%20aqui"
    target="_blank"
    style="position:fixed" class="figura">
    <svg enable-background="new 0 0 512 512"  version="1.1" viewBox="0 0 512 512" xml:space="preserve" xmlns="http://www.w3.org/2000/svg"><path d="M256.064,0h-0.128l0,0C114.784,0,0,114.816,0,256c0,56,18.048,107.904,48.736,150.048l-31.904,95.104  l98.4-31.456C155.712,496.512,204,512,256.064,512C397.216,512,512,397.152,512,256S397.216,0,256.064,0z" fill="#4CAF50"/><path d="m405.02 361.5c-6.176 17.44-30.688 31.904-50.24 36.128-13.376 2.848-30.848 5.12-89.664-19.264-75.232-31.168-123.68-107.62-127.46-112.58-3.616-4.96-30.4-40.48-30.4-77.216s18.656-54.624 26.176-62.304c6.176-6.304 16.384-9.184 26.176-9.184 3.168 0 6.016 0.16 8.576 0.288 7.52 0.32 11.296 0.768 16.256 12.64 6.176 14.88 21.216 51.616 23.008 55.392 1.824 3.776 3.648 8.896 1.088 13.856-2.4 5.12-4.512 7.392-8.288 11.744s-7.36 7.68-11.136 12.352c-3.456 4.064-7.36 8.416-3.008 15.936 4.352 7.36 19.392 31.904 41.536 51.616 28.576 25.44 51.744 33.568 60.032 37.024 6.176 2.56 13.536 1.952 18.048-2.848 5.728-6.176 12.8-16.416 20-26.496 5.12-7.232 11.584-8.128 18.368-5.568 6.912 2.4 43.488 20.48 51.008 24.224 7.52 3.776 12.48 5.568 14.304 8.736 1.792 3.168 1.792 18.048-4.384 35.52z" fill="#FAFAFA"/></svg>
</a>
   </div>
<header class="container">
    <img src="Logosemfundo.png" class="conteiner">
    <nav>  
        <a href="index.html">Inicio</a></li>
        <a href="sobre.html">Sobre</a></li>
        <a href="procedimentos.html">Procedimentos</a>
        <a href="contato.html">Contato</a>
         
    </nav> 
</header>
   
  <main class="article">
    <span>A Clinica da Dra. Roberta Lima conta com um ótimo atendimento para você.</span> 
    <br>
    <span>A clinica tem um espaço limpo e higienizado.</span> 
    <br>
    <span>Especialista em estética avançada</span>
    <br>
    <span>Harmonização facial e corporal</span>
    <br>
  </main>   
  <main class="menu">  <!--inicio do conteudo--> 
   <img src="img/Boca.jpg" width="300px"> 
   <br><br>
  <article>  
       <h2><strong>Aqui está alguns dos nossos procedimentos </strong></h2> 
       <br><br>
        <h3>Botox</h3>  
        <h3>Skin Booster</h3>  
        <h3>Preenchimento de malar</h3>
        <h3>Preenchimento de olheiras</h3>
        <h3>Preenchimento labial</h3>
        <h3>Biostimulador de Colágeno</h3> 
    </article>
   </main> <!-- fim do conteudo -->  
  <footer>
    <span><a href="https://www.google.com/maps/place/Dra+Roberta+Lima+-+R.+Comerc.+Jos%C3%A9+Pontes+de+Magalh%C3%A3es,+70+-+Jati%C3%BAca,+Macei%C3%B3+-+AL,+57036-220/@-9.6522798,-35.7010946,16z/data=!4m2!3m1!1s0x70145da23df307d:0x24a4a56a42bcfadd"> <img class="lock"  src="img/localizacao.png">R. Comerc. José Pontes de Magalhães, 70 - Jatiúca, Maceió - AL, 57036-220 </a></span> 
    <form class="fomulario" action="mailto:heracton18@gamil.com" method="POST" enctype="text/plain"> 
          <label for="">Nome completo</label>
          <input type="text" name="nome" id="nome" required> 
          <br>
          <label for="">E-mail</label> 
          <input type="email" name="email" id="email" required> 
          <br>
          <label>Data</label> 
          <input type="date" name="data" id="data" required> 
          <br>
          <p>Informe o seu sexo:</p>
          <input type="radio" name="faminino" id="faminino" value="feminino" required> 
          <label for="Feminino">Feminino</label>
          <input type="radio" name="masculino" id="masculino" value="masculino" required> 
          <label for="Masculino">Masculino</label>
          
      </form>
   </footer>
  <script src="main.js"></script>
</body>
</html>  @charset "UTF-8"; 

* {
  margin: 0; 
  padding: 0; 
}

body {
  font-size: 15px;  
}

.numero {
      background-color: #C59E46;
      text-align: right;
      color: black;
      padding-right: 15px;
      border-radius: 10px 10px 0px 0px; 
    }
    
    .numero a {
      position: relative;
      right: 170px;
      width: 20px;
    }
    
.link {
  text-decoration: none; 
  text-align: right;  
  color: white;  
  margin: 10px; 
} 

.link:hover {
  background-image: linear-gradient(to right #42445A, #B9923F);
  color: black; 
}
 
  header {
  padding: 0;
  background-image: linear-gradient(to right,  #42445A, #B9923F);
  min-width: 200px; 
  padding-top: 30px;
  font-size: 15px;
  color: black;
} 

.container {
  display: flex; 
  align-items: center;  
  bottom: 10px; 
}

.conteiner {
    width: 250px;
    padding-left: 600px;
    max-width: 300px;
    min-width: 10px;
}
  
  header img, nav {
    display: inline-block; 
  }


.boca {
  display: inline-block;
  width: 10px; 
}

nav {
 text-align: right;
 top: 50px; 
 padding-bottom: 10px;
 padding-right: 10px;
 padding-left: 120px;
 
}

nav > a {
  color: white;
  padding: 10px;
  text-decoration: none;
  font-weight: bold; 
  border-radius:20px; 
  transition-duration: 0.5s;  
  
}

nav>a:hover {
  background-image: linear-gradient(to right #42445A, #B9923F);
  color: green;
}

.main {
  font-size: 16px; 
  text-align: center; 
} 

.article > span {
  font-size: 16px; 
  padding-left: 10px; 
  display: inline-block; 
  text-align: center; 
  padding-left: 500px; 
  padding-bottom: 10px; 
}

main img {
  padding-left: 500px; 
}

article {
  font-size: 15px; 
  background-color:  #B9923F; 
  border-radius: 10px 10px; 
  padding: 10px; 
  margin: 10px 10px solid blue; 
  
} 

article > h2 {
  text-align: center; 
  font-size: 20px; 
  font-family: 'Roboto', sans-serif; 
  padding-top: 10px; 
}  

article > h3 {
  text-align: center; 
  font-size: 17px; 
  font-family: Arial, Helvetica, sans-serif; 
}

  footer {
     background-image: linear-gradient(to right, darkgray, lightgray);  
     padding: 10px; 
  } 
  
  .formulario {
    display: inline-block; 
    font-size: 15px; 
    padding: 5px; 
    color: black; 
  }
  
 footer a {
   text-decoration: none;  
 } 
 
 footer a:hover {
  background-image: linear-gradient(to right, darkgray, lightgray);  
   color: black; 
 }
 
 .lock {
   width: 25px; 
   padding: 5px;
 }
