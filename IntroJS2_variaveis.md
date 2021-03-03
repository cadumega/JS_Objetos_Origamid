Variáveis

<script type="text/javascript">
function ligar() {
    var nome ='cadu';
    var idade = 31;
    var casado = true;
    document.getElementbyID('xti').src= 'img/xlamp_on.png';

}


# Com essas variáveis declaradas podemos imprimir os valores dessas variáveis.
alert(nome);

3 variáveis declaradas com 3 tipos primitivos diferentes de variáveis.
//string   //number   //boolean

obs: não utilizar números no início da variável, pode iniciar com $ ou _ (utilizados mais para bibliotecas js)

obs2: nomes fáceis para identificar. Letras maisculas reservamos para constantes ,de dados que não podem ser modificados, ou identificações de objetos ex. Pessoa, Carro, primeiroNome. cammel case para variaveis com nomes compostos.

#palavras reservadas se atentar


<script type="text/javascript">
function ligar() {
    var nome ='cadu';

    document.getElementbyID('xti').src= 'img/xlamp_on.png';

}

\\ para representar uma barra \ para representar o caracter.
\n quebra de linha

◘ Outros tipos primitivos.◘ 
•undefined   var nome;

•null  
var nome;
nome = null;

•NaN #not a number#
var nome;
nome = null;
nome = 3* 'pessoas';


◘ Constantes não conseguimos alterar a variável,não poderei alterar o valor.
const HORAS_DO_DIA = 24;      #criar com letra M, fácil identificação.

obs: Representar o espaço do território brasileiro, criaria uma constante.
obs2: Representar a quantidade da população brasileira, teria que ser variável, pois muda de hora em hora a quantidade.