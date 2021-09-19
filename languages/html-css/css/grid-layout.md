# CSS Grid Layout

Grid é uma forma fácil de organizar os elementos de uma página em colunas e fileiras. Segue exemplos básicos de uso do mesmo.

## Iniciar uma grid

<pre>
  <code>
    .container {
      display: grid;
    }
  </code>
</pre>

#### ou

<pre>
  <code>
    .container {
      display: inline-grid;
    }
  </code>
</pre>

- Ao declarar como <code>grid</code> declaramos uma grid em bloco.
- Ao declarar como <code>inline-grid</code> declaramos uma grid em linha.

## Definir colunas

<pre>
  <code>
    .container {
      grid-template-columns: 1fr 1fr;
    }
  </code>
</pre>

- <code>1fr</code> é uma forma de fracionar uma área, ao usá-lo duas vezes estou declarando que deve haver duas colunas com a mesma largura (50% - 50%).
- Se <code>1fr</code> for usado depois ou antes de alguma outra medida ele preencherá todo o espaço restante.

## Definir linhas (rows)

<pre>
  <code>
    .container {
      grid-template-rows: repeat(3, 1fr);
    }
  </code>
</pre>

## Manipulando elementos pelas colunas e linhas

<pre>
  <code>
    .item {
      grid-column-start: 1;
      grid-column-end: 2;
      grid-row-start: 2;
      grid-row-end: 3;
    }
  </code>
</pre>

## Definindo áreas

<pre>
  <code>
    .container {
      grid-template-areas: "item1 item3" "item2" ;
    }

    .item1 {
      grid-area: item1;
    }

    .item2 {
      grid-area: item2;
    }

    .item3 {
      grid-area: item3;
    }
  </code>
</pre>

# Alinhamentos

<pre>
  <code>
    .item {
      justify-self: start;
      justify-self: stretch;
      align-self: end;
    }
  </code>
</pre>

- <code>justify-self</code> alinha o elemento dentro da coluna e linha em que se encontra
- <code>jusity-self: stretch;</code> preenche todo a area em que o elemento se encontra

# Material complementar

<a href="https://css-tricks.com/snippets/css/complete-guide-grid/">CSS Tricks</a> <br />
<a href="https://developer.mozilla.org/en-US/docs/Web/CSS/grid">MDN</a>
