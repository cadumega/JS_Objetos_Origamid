◘Javascript◘

Pessoa                                     (objetos)
    altura,peso,profissão                 (propriedades)
        andar(),dormir(),trabalhar()      (métodos/funções)

Para acessar as propriedades e métodos, temos uma sintaxe pŕopria

Pessoa.altura;      acessar propriedade , ; para finalizar a sintaxe
Pessoa.andar();      acessar método ou função


◘ 3 Categorias de objetos ◘

• Objetos internos (string, date,number)

• Objetos do Browser (window, document)      windows é objeto raíz

• Objetos personalizados



Dentro do objeto windows, temos a função alert();
var largura = window.innerWidth         (largura do objeto window)

objeto document, contém o título do nosso documento.
window.alert(window.document.title); #irá aparecer o título da janela no alert


◘ Ações de elementos, são acionadas atráves dos manipuladores de Eventos ◘

Dentro dos elementos html, temos os atributos para manipulações dos eventos.
Como o onclick= alert('Ola')        efeito de clicar na imagem.

onmouseover= alert('Ola')       disparado elemento JS ao passsar o mouse
<body onload= " alert('carregado');">         quando dispararmos um elemento, quero disparar um JS no carregamento da página

<script type="text/javascript">
function ligar() {
        document.getElementbyID('xti').src= 'img/xlamp_on.png';
}

obs:
 #getElement recupero um elemento por atributo/método id,name,por tipo da tag.#
Quando clicar na imagem, executa determinada função, que recupera a imagem, e altera o atributo src da imagem, passando outro valor. 

<body>
<img id ='xti' src='img/xlamp_off.png' />
</body>

