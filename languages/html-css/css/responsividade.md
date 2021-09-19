# CSS @media rules

## Básico da responsividade com @media

### Medidas com resolução de tela até n píxeis

<pre>
  <code>
    @media screen and (max-width: 800px) {...}
  </code>
</pre>

**Ou**

<pre>
  <code>
    @media (max-width: 800px) {...}
  </code>
</pre>

> É recomendado que se use a primeira opção, pois ao não especificar que é screen o css pode entender que se trata do outras medidas, por exemplo o texto

### Medidas com especificação

<pre>
  <code>
    @media only screen and (max-width: 800px) {...}
  </code>
</pre>

- Em navegadores antigos não haverá diferença ao usar only e apenas colocar screen, por exemplo no IE 6-8

### Use um shorthand

<pre>
  <code>
    @media (width > 700px) {...}

    @media (height > 500px) {...}

    @media screen and (height > 500px) {...}

    @media only screen and (height > 500px) {...}
  </code>
</pre>

### É possível colorcar mais de uma medida na regra

<pre>
  <code>
    @media 
    (height > 500px)
    (width < 400px>) {...}
  </code>
</pre>

## Exemplo de código

<pre>
  <code>
    @media (min-width: 500px){
      body {
        background: #ddd;
        font-size: 98%;
      }

      main {
        margin: auto;
      }
    }
  </code>
</pre>

> Nesse caso a regra refere a medida de tela menor que 500px

- Caso haja dúvidas ou se quiser complemento leia <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/@media">isso</a>
