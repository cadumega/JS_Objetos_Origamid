Estrutura de Loop do while
Não temos inicialização e nem atualização dentro da estrutura while.
Colocamos somente o teste da variável.

while (teste) {...}

for (var i=o; i<3; i++) {...}


___
Atualizamos a variável dentro do bloco. Equivalente a estrutua for.

var i=o;
var texto = '';
while (i<3) {
 	texto += i;
	i++;
}
alert(texto);

__
Executa o bloco de script quando a avaliação for verdadeira.
#Executa pelo menos uma vez do while , depois de avaliar uma condição
while só executa o bloco caso a condição seja verdadeira.


var i=o;

do {
...
} while (teste);

while (i<3) {
	i++;
}

 var i=o
while (false) {
	alert (i);
}.

do `{
}	while (false);