Estrutura para exceções (erros)

#Identificar e tratar erros em javascript
#script abaixo, identificar o erro:

var x=a ;
var b=x +10;
alert(b);

ao executar... 
não apresenta a mensagem de alerta, em algum momento erro aconteceu e parou de executar o script
verificar no console . var x=a;   "a is not defined"

#Try tentar executar o código, e se encontrar algum problema pegue o problema com catch para recuperar o erro
,passar um nome "e" para atribuir o erro caso encontre.
Disparar uma mensagem de alerta, para mostrar os atributos do Objeto Error

try {
	var x=a ;
var b=x +10;
alert(b);
} catch (e) {
	alert(name + "-" + e.message);
}

Reference Error "a is not defined"

#temos o outro método toString

try {
	var x=a ;
var b=x +10;
alert(b);
} catch (e) {
	alert(e.toString());
}	

Reference a is not defined

try {
	var x=a ;
var b=x +10;
alert(b);
} catch (e) {
	alert(e.toString());
} 

__
#Usar palavra reservada throw, identifica e lança o erro para ser capturado em outra estrutura como a catch.
Iremos fazer um script para informar um número, usando o elemento prompt do objeto window, 
mais abaixo iremos verificar se o número que foi informado é menor que 10 com if,
iremos lançar a excessão com throw (pode lançar objeto error como qualquer outro elemento ,string tb.


var x = prompt('Informe numero maior que 10")
try {
	if (x<10) {
		throw "número menor que 10";
	}
	alert(x);

} catch (e) {
	alert(e);
} 

____
Dentro de potencia iremos criar um outro objeto.
Como criar objetos , utilizar dois pontos para declarar e virgula ao final
Como podemos apresentar ,qts cavalos de potencia o carro tem?
Para alterar o escopo, para recuperar de maneira mais fácil podemos utilizar palavra chave with,
falar que quero criar um escopo diferente, acessar com determinada estrutura

var Carro = {
	marca : "Nissan",
	modelo :"XYZ',
	potencia : {
		cavalos: "350",
		velocidade: "320km/h" 	
	}
};
with (Carro.potencia) {
	alert(cavalos);
	alert(velocidade);
}
_____

Objeto Error
	• message      #trás detalhes do erro, como variável indefinida
	• name 		#tipo de erro
	• toString ()	#tipo de erro + a mensagem

tipos de erro:
EvalError 	Erro usando eval ()
RangeError 	Número extrapola limites
ReferenceError 	Referência a valor indefinido
SintaxeError 	Erro de Sintaxe da linguagem
TypeError 	Operando diferente do esperado
URIError 	Uso errado de funções URI