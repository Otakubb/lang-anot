# Alinhamento ao centro

## Alinhamento de texto

<pre>
  <code>
    text-align: center;
  </code>
</pre>

- Há muitos outros valores para o text-align como start, end e <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/text-align">mais</a>

## Alinhamento com flexbox

<pre>
  <code>
    display: flex;
    justify-content: center; //horizontal
    align-items: center; //vertical
  </code>
</pre>

- Essa forma deve ser aplicada em um elemento pai do manuseado, ela pode não funcionar em alguns casos especificos
- Caso tenha dúvidas leia <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout">isso</a>

## Alinhamento com margin

<pre>
  <code>
    display: block;
    margin-left: auto;
    margin-right: auto;
  </code>
</pre>

**Ou usando um shorthand**

<pre>
  <code>
    display: block;
    margin: auto;
  </code>
</pre>

- É mais usado para alinhar containers, mas pode ser usado em qualquer circunstância
- Encontre mais <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/margin">aqui</a>
