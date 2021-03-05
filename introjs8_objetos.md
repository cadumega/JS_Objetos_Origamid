Objetos JavaScript

3 tipos de dados primitivos, informações do estado mais bruto, não são objetos.

String, boolean, number.  Dados brutos, informação em si, não apresentam funções.

Os Objetos podem realizar algumas ações, que chamamos de Funções ().

Pessoa
	pessoa.sexo, .profissao
	pessoa.dormir(), .comer() , .trabalhar()

Temos Objetos nativos da linguagem, indepente do browse.
Object	Function   	objeto mais genérico, criar funções
Array	ReferenceError  Listas
Date	SintaxeError	Manipular datas,séries de funções e atributos 
Math	TypeError	Cálculos matemáticos
RegExp	UriError	Manipulações de expressões regulares, validações de informações



var nome = 'Ricardo';
alert (typeof(nome);

string

quantos caracteres tem na string , fazendo por debaixo dos panos.
Envolve o objeto com o tipo string, faz a chamada ao atributo ou função e

var nome = 'Ricardo';
alert (nome.length);  || alert new String(nome).length)  


Chamadas de funções e atributos de objetos, é melhor que já crie com o objeto equivalente ex.
var nome = new String ('Ricardo');  , muitas chamadas especifica o tipo de objeto da variável.

De forma natural...

var nome = 'Ricardo';
alert(nome.toUpperCase());



Objeto Boolean

var b= true;
alert(b);

var b= true;
alert(typeof(b));

#criar a variável com tipo de dado Objeto.

var b= new Boolean(true);
alert(typeof(b));

"Zero, null, NaN e a string vazia são inerentemente false. todo o resto é inerentemente true.