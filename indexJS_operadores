Estudo dos operadores JS

◘ arqoperador.js

alert (2 + 3);

<,>,<=,>=
.       acessar propriedade do objeto
&& and      || or      ! not
[] indexar arrays


var x = 9 + 4;
alert(x) ;
13

Concatenar
var x = "9" + "4";
alert(x) ;

Lembrar da ordem de precedência.
Incremento ++x e decremento -- .


Operadores de comparação

== 
===
!= diferente
!==
> < >= <=

Operadores lógicos
&& and      || or      ! not

var x = 6;
alert( (x >=1 ) && (x <=10));
true

|| precisa só de uma instrução verdadeira, para retornar boolean true.


var x =6;
alert(!(x >=1)); 
false                passa a ser o inverso da avaliação inicial.

Operadores de atribuição , maneira simplificada 
var x = 6;
x = x + 3;        simplificando..        x+=3;

Operadores especiais
new , this, typeof, (), instanceof,in,delete , ?: operador ternário

var idade = 21;
var x = (idade >=18) ? "maior de idade" : "menor de idade";
alert(x);
#maior de idade            que irá retornar

var idade = 21; sexo = "masculino", nacionalidade = "brasileiro
var x = (idade >=18) ? "maior de idade" : "menor de idade";

Pessoa = {
    nome: "Fulano"
}
alert (Pessoa.nome);
delete Pessoa.nome;
alert(Pessoa.nome);
Fulano.... Undefined    #pq removi a propriedade nome

Pessoa = {
    nome: "Fulano"
}
alert ("nome" in Pessoa);
alert('email' in Pessoa);
True........ False       #existe a propriedade nome dentro do objeto Pessoa, mas não existe a propriedade e-mail dentro do objeto Pessoa.

var idade = new Number(31) ;
alert(idade instanceof Number);
# retorna true que é uma instância do objeto Number, se fosse objeto String daria false.

new cria um novo objeto.

alert(this.document.title);        # 
function oi () {
  this
}                                   # irá se referir a essa função e não no objeto window que esta fora, no contexto externo.

alert(typeof(3));
#number                     retorna o tipo de dado

___________
◘ Cálculo de IMC    
IMC = peso / (altura)²

Criar um formulário simples, onde iremos preencher com os dados devidos.

◘ arqeximc.js  , precisamos capturar os valores preenchidos nos campos.

function calcularIMC() {
   var formulario = document.getElementById('formulario');
    
    var kilos = formulario.kilos.value;
    var metros = formulario.metros.value;
    var centimetros  = formulario.centimetros.value;
    
     var altura = (metros * 100) + centimetros;
     
         var imc = kilos / (altura * altura);
                
}

 # usar alert(centimetros);            esta recuperando o valor corretamente     
#esta tratando os valores como string, descobri pelo alert.typeof(kilos));              
# parseInt transforma um valor string em um valor inteiro
# também temos a possibilidade de usar um operador + , operador unário com objetivo de aplicar,declarar que a variável terá esse sinal, se o operador não for valor numérico, irá tentar converter, irá forçar a conversão em um número. Sendo valores positivos não terei problema em usar esse operador unário.
  
    var kilos = +formulario.kilos.value;

function calcularIMC() {
    var formulario = document.getElementById('formulario');
    
    var kilos = +formulario.kilos.value;
    var metros = +formulario.metros.value;
    var centimetros  = +formulario.centimetros.value;
    
     var altura = (metros * 100 + centimetros)/100;
     
     var imc = kilos / (altura * altura);
  
      formulario.imc.value= imc.toFixed(2);    #para colocar o valor no campo
                          #p/ 2 casas decimais, existe um método para fixar as casas decimais toFixed(number);        
}

◘ arqeximc.html
<html xmlns=http://www.w3.org/1999/xhtml">
  <head>
    <title> JavaScript Aula </title>
     <scipt type=text/javascript" src='js/aula.js'></script>
     <style type ='text/css'>
          img, table {width:165px;}
          fieldset {width:140px;}
          label {display:block; float:left;}
          label, input {width:68px; margin:3px 0;}
          th, td {border:1px solid #ccc; font-size:0.8em; }
      </style>
  </head>
<body>

<img src="img/imc.jpg" alt="imc" />

<form id='formulario'>
  <fieldset>
    <legend> Cálculo do IMC </legend>

    <label for='kilos'>Kilos:</label>
    <input type='text' name ='kilos' />

    <label for='kilos'>Metros:</label>
    <input type='text' name ='metros' />

    <label for='kilos'>cm:</label>
    <input type='text' name ='centimetros' />

    <a href='#' onclick='calcularIMC().">Calcular</a>
  <fieldset>
</form>

  <table>
    <tr><th>IMC</th><th>Classificação</th></tr>
    <tr><td>&lt; 20</th><th>Abaixo do Peso</td></tr>
    <tr><td>20 a 25</th><th>Peso Ideal</td></tr>
    <tr><td>25 a 30</th><th>Sobrepeso</td></tr>
    <tr><td>30 a 35</th><th>OBesidade Moderada</td></tr>
    <tr><td>35 a 40</th><th>Obesidade Severa</td></tr>
    <tr><td>40 a 50</th><th>Obesidade Mórbida</td></tr>
    <tr><td>&gt; 50</th><th>Super Obesidade</td></tr>
  </table>

  </body>
</html>





