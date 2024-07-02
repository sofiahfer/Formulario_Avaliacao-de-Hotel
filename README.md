# Formulario_Avaliacao-de-Hotel
Fiz um formulário que avalia um hotel em uma pagina online com HTML e CSS, para a aula na escolas SESI de Floripanópolis aonde os alunos poderiam escolher o assunto da pagina online. 
<br><hr>
<h3 align="center">Fotos do formulário</h3>  
https://github.com/sofiahfer/Formulario_Avaliacao-de-Hotel/assets/162721460/5ee91cc7-5bc6-4786-af03-543821e5110e
<br> https://github.com/sofiahfer/Formulario_Avaliacao-de-Hotel/assets/162721460/56d0c3fb-a6a1-49c5-9315-7f43b695e503
<hr>
<h3 align="center">HTML do Formuláirio</h3>
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pesquisa de Satisfação</title>
    <link rel="stylesheet" href="formulario.css">
</head>
<body>
    
    <div class="container">
     <h1>Avalie o nosso Hotel</h1>
     <div class="textos">
         <h3>Antes de ir para a avaliação, quais são as suas informações!</h3>  
    </div>
    <section class="info">
         <label for="date">Seu Nome: </label>
         <input type="name" id="name" name="name" placeholder="name"><br><br>
    
         <label for="date">Seu Email: </label>
         <input type="email" id="email" name="email" placeholder="email"><br><br>
   
         <label for="date">Qual foi o dia, do inicio da sua hospedagem: </label>
         <input type="date" id="date" name="data" placeholder="data"><br><br>

         <label for="date">Qual foi o ultimo dia da sua hospedagem: </label>
         <input type="date" id="date" name="data" placeholder="data"><br><br>
    </section><hr>
    <div class="textos">

         <h4>1. Como você classifica o nosso atendimento? </h4>

    </div> 
    <section class="emocoes">
         <label for="">😁</label>
         <input type="radio" name="emocao1"><br><br>

         <label for="">😊</label>
         <input type="radio" name="emocao1"><br><br>
    
         <label for="">😐</label>
         <input type="radio" name="emocao1"><br><br>

         <label for="">😠</label>
         <input type="radio" name="emocao1"><br><br>
    </section><hr>
    <div class="textos">
         <h4>2. Como você avalia a nossa estrutura? </h4>
    </div>
    <section class="emocoes">
         <label for="">😁</label>
         <input type="radio" name="emocao2"><br><br>
     
         <label for="">😊</label>
         <input type="radio" name="emocao2"><br><br>
    
         <label for="">😐</label>
         <input type="radio" name="emocao2"><br><br>

         <label for="">😠</label>
         <input type="radio" name="emocao2"><br><br>
    </section> <hr>
    <div class="textos">
         <h4>3. Como você avalia a limpeza do nosso estabelecimento? </h4>
    </div> 
    <section class="emocoes">
         <label for="">😁</label>
         <input type="radio" name="emocao3"><br><br>
     
         <label for="">😊</label>
         <input type="radio" name="emocao3"><br><br>
    
         <label for="">😐</label>
         <input type="radio" name="emocao3"><br><br>

         <label for="">😠</label>
         <input type="radio" name="emocao3"><br><br>
    </section><hr>
    <div class="simounao">
          <h4>4. Você voltaria a se hospedar conosco? </h4>
         <label for="">Sim</label>
         <input type="radio" name="simounao1">
    
         <label for="">Não</label>
         <input type="radio" name="simounao1"><hr>

         <h4>5. Você indicaria o nosso hotel para outras pessoas? </h4>
         <label for="">Sim</label>
         <input type="radio" name="simounao2">
   
         <label for="">Não</label>
         <input type="radio" name="simounao2"><hr>
      
         <h4>6. Você indicaria o nosso hotel para outras pessoas? </h4>  
         <label for="">Sim</label>
         <input type="radio" name="simounao2">
 
         <label for="">Não</label>
         <input type="radio" name="simounao2"><hr>
    </div>
    <section class="final">
         <br><h3>Obrigado, por avaliar o nosso hotel!</h3>
    </section>
    <div class="botao">
         <button>Envie!</button>
    </div>
    </div>
</body>
</html>

<hr><h3 align="center">CSS do Formulário</h3>

body{
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-image:url(https://img.belmond.com/f_auto/t_2580x1451/photos/cat/cat-ext04.jpg);
    background-repeat: no-repeat;
    background-position: center;
    background-size: 300%;
}
.container{
    background-color: #ebe6e6d5;
    max-width: 60%;
    padding: 1%;
    border-radius: 15px;
    box-shadow: 10px 10px 10px #16161667;  
    align-items: center;
    margin: auto; 
    justify-content: center;
}
h1,h2,h3{
    font-family: Georgia, 'Times New Roman', Times, serif;
}
h1{
    text-align: center;
}
h4{
    font-family: Georgia, 'Times New Roman', Times, serif;
    width: vertical-aling;
    text-align:inherit;
    border: solid 0px;

}
.textos{
    text-align: left;
    border: solid 0px;
    margin-left: 200px;
}
.emocoes{
    width: fit-content;
    border: solid 0px;
    margin-left: 280px;
}
.simounao{
    border: solid 0px;
    text-align: center;
}
.info{
    text-align: left;
    border: solid 0px;
    margin-left: 210px;
}
input{
    color: burlywood;
    border: #ebe6e6;
    width: 150px;
    padding: 0.5%;
    border-radius: 5px;
}
input::placeholder{
    color: burlywood;
}
.final{
text-align: center;
}
.botao{
text-align: center;
}
