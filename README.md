<html>
  <body style = "backgraund-color:black;">
    <titulo>
      Imersão Dev - Aula 01</titulo>
    </head>
  <body>
    <div class="container"

      <h1 class= "page-title">
    Converssor de Moedas</h1>
  <p class= "page-subtitle">
    Descubra os valores em U$</p>
  <div style ="Text-align: center">
    
  <img src = "https://i.pinimg.com/originals/5a/12/64/5a126422a7cd5f60f503084ff4274a8b.gif" class ="moedas "  alt ="moedas"
       </div>
  <A hret ="https://www.google.com.br  "
     alvo ="blanck">
    <img src = "https://i.pinimg.com/originals/81/5a/4c/815a4cb42358b9a5e114e595bb0aed18.gif      "
         alt ="TRUMP"
         
         class ="TRUMP"
         
         </a>
    </body>
</html>



body {
  font-family:"Roboto Mono", monosoace;
  min-height: 400px; 
  background-image: url('https://i.pinimg.com/originals/5a/12/64/5a126422a7cd5f60f503084ff4274a8b.gi');
  background-color:00000;
  background-size: 100vh;
  background-position: center bottom;
  background-repeat: no-repeat;  
}
.container{
  text-align: center;
  padding: 20px;
  height: 100vh;
 }
.page-title {
  color: #fffff;
  margin: 0 0 5px;
   
}
.page-logo {
  width: 200px;
}
.altura-logo{ width: 40px;
position: absolute;
top: 20px;
right : 10px;}



var valorEmDolar = prompt ("Qual o valor em dolar que deseja converter?")
var valorEmDolarNumero = parseInt(valorEmDolar)
var  valorEmReal = valorEmDolarNumero *5.51
alert("R$" + valorEmReal)
