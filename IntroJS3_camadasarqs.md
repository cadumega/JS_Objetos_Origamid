Criar camadas dos arquivos, separar os arquivos HTML CSS e JS.

◘arq.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <script src= 'arqaula.js'></script>
</head>
<body>
  <img id='xti' onclick='ligar()';
        src='img/xlamp)off.png" /> 
</body>
</html>


◘arq.css

<style stype'text/css'>
  body {background-color: #000; }
  #xti {display:block; margin:20px auto; }
</style>


◘ 3 formas de adicionar java script
• direto dentro da tag - inline
• estilo incorporado, dentro do doc html - Incorporado ao doc
• modelo externo, link ao doc html - Arqs profissionais trabalham dessa forma!!
Tanto as integrações com as folhas de estilo e de marcação html.


◘ arqaula.js    [ex.arquivo]  , + organizado o arq separado.
Comentário ,posso colocar várias linhas de comentários.

/*
função: ligar()
autor: Carlos Mega
descrição: apresenta o nome do usuário e liga a lâmpada
*/

function ligar() {
    var nome = prompt('Qual o seu Nome ?');
    alert('Prazer em conhecer você' + nome);

    document.getElementbyID('xti').src= 'img/xlamp_on.png';
}