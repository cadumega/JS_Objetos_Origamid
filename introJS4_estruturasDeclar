◘Declarações e Estruturas◘

• Estruturas de Controle

var,function,return,

•Condicionais
if/else,switch         case break,default

•Loops
for/in,while,do

•Exceções   
,throw,try/catch/finally,with
__
declarar as variáveis sem atribuir valor, serão undefined
var a , b , c;
var a = 1;



function dividir (x,y) {
 alert (x/y);
}

dividir(6,2);

retornar o valor resultante de uma função, a

function dividir (x,y) {
 return (x/y);
}
alert (dividir(6,2));

__
Estruturas condicionais
Se (if fizer sol vamos ao clube senão (else) vamos ao shopp.

formas mais simples, com mais opções de testes:

var idade = 10;
if(idade<11) {
 alert('criança')
}
# irá executar o bloco if, dando o alert criança. 

var numero = 10;
if((numero % 2) == 0) {
 alert('par')
} else {
 alert('impar');
}

var passou = true;
if (passou) {
 alert('contratado(a)');
} else {
 alert('estude mais');
}



var idade = 28
if(idade<=11) {
 alert('criança')
}
else if ( idade >11 && idade <=16 )
{
 alert ('pré-adolescente');
}
else if ( idade >16 && idade <=21 )
{
 alert ('adolescente');
}
else if ( idade >21 && idade <=60 )
{
 alert ('adulto');
}
else
{
 alert ('idoso');
}


var nota = 6;
if (nota >=7)
{
 alert('passou');
}
else
{
 alert('reprovou');
 if (nota ==6) {
  alert('você esta em recuperação');
 }
}

◘ Estrutura condicional Switch  , executar testes e executar operações cada determinada expressão seja verdadeira.
Vantagem de comparar com vários valores diferentes.
Ao colocar a palavra break, eu paro com as avaliações.

Valores que serão comparados ao switch já declarado. Podemos suprimir o default, mesma coisa de colocar o if sem o else.
Podemos suprimir o break, exemplo abaixo.

var sexo = 'M';
switch (sexo)
{
 case 'M':
  alert('Macho');
  break;
 case 'F':
  alert ('Femea');
  break;
 default:
 alert ('Indefinidio');
}

|| Poderia fazer também seguindo a condicional if && else. 
obs:preciso trazer a variável para comparar ao meu caso, no swithc não preciso.

var sexo = 'M';
if (sexo =='M')       
{
 alert ('Macho');
}
else if (sexo =='F')
{
 alert('Femea');
}
else
{
 alert('Indefinido');
}

• executar o script caso a condição seja verdadeira, ou pular o bloco do script caso não seja verdadeiro.
var tecnologia = 'java';
swtich (tecnologia) {
 case 'java':
 case 'c++':
 case 'javascript':
 case 'c#':
  alert ('linguagem de programação');
  break;
 case 'sqlserver':
 case 'postgresql':
 case 'oracle':
  alert ('banco de dados');
  break;
 default:
  alert('tecnologia não conhecida');
}

function calcularIMC() {
  var formulario = document.getElementById("formulario");
  var kilos = +formulario.kilos.value;
  var metros = +formulario.metros.value;
  var centimetros = +formulario.centimetros.value;
  var altura = (metros * 100 + centimetros)/100;
  var imc = kilos / (altura * altura);
  var resultado = +formulario.imc.value;

  formulario.imc.value = imc.toFixed(2);
  resultado = imc;
  
  if(resultado < 20) {
   alert ("Abaixo do peso");
  }
  else if( resultado >= 20 && resultado <= 25) {
   alert ("Peso ideal");
  }
  else if( resultado > 25 && resultado <= 30) {
   alert ("Sobrepeso");
  }
  else if( resultado > 30 && resultado <= 35) {
   alert ("Obesidade moderada");
  }
  else if( resultado  >35 && resultado <= 40) {
   alert ("Obesidade severa");
  }
  else if( resultado > 40 && resultado <= 50) {
   alert ("Obesidade mórbida");
  }
  else {
    alert ("Super obesidade");
  }

}


◘Estrutura de Loop for   - Estrutura de Repetição
Estrutura de repetição que executa o bloco várias vezes, até que seja alcançado determinada condição.

for, for/in, do, while

Estrutura semelhante ao if.

for(var i=0; i <3; i++) {...}

Elementos: 
Inicialização, Inicializa a variável
Teste,  testa a variável, é verdadeira
Ação,  executamos o bloco
Atualização, atualiza a estrutura

var texto = "";
for(var i=10; i >0; i++)
{
	texto = texto + i;                 ||     texto +=i + ",";
}
alert (texto);

#Assim que essa condição não for mais verdadeira, passa a executar o script logo após o bloco.
#separo os elementos com vírgula "," 


var texto = "";
for(var i=0; i <20; i++)
{
	if(i%2 == 0) {
	if(i==20)
		texto +=i;
	} else {
		 texto +=i + ",";
}
alert (texto);

#tirar a vírgula do final, ex acima.

# estrutura com break, parar estrutura ou estrutura condicional


var texto = "";
for(var i=0; i <20; i++)
{
	if(i%2 == 0) {
	if(i==20) {
		texto +=i;
		break; 		
	}
		 texto +=i + ",";
}

#cuidado com loops infinitos, XXXXXXXXX
for (var i=0; true; i++)
{
	alert (i);
}
alert (texto);