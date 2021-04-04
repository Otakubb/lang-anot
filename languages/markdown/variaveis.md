# Variáveis

Variáveis no Markdown sim isso é posivél no markdown ... 

Para setar uma variável no Markdown é bem simples você só vai precisar dos colchetes (`[]`)

Tá mas para que serve? Sabe quando seu projeto utiliza muitos links? É pra isso que ele serve ... 

Exemplo:
```md
* [MarkDown](https://github.com/Otakubb/lang-anot/tree/main/languages/markdown)
	- Dicas
		* [Variáveis](https://github.com/Otakubb/lang-anot/tree/main/languages/markdown/variaveis.md)

* [HTML & CSS](https://github.com/Otakubb/lang-anot/tree/main/languages/html-css)

* [JavaScript](https://github.com/Otakubb/lang-anot/tree/main/languages/javascript)
```

O código fica feio desse jeito ... então nós usamos as variáveis ...

Sintaxe das variáveis do Markdown:
```
[url]: https://www.example.com/url
[url_Google-br] https://www.google.com.br
```

Para usar elas você coloca assim:
```
[Título][url]
[Título][url_Google-br]
```

Aquele código ficará assim depois de ter adicionado as variáveis:

```md
* [MarkDown][Url_MD]
	- Dicas
		* [Variáveis][Url_Variaveis_MD]

* [HTML & CSS][Url_HTML_CSS]

* [JavaScript][Url_JS]

[Url_MD]: https://github.com/Otakubb/lang-anot/tree/main/languages/markdown
[Url_Variaveis_MD]: https://github.com/Otakubb/lang-anot/tree/main/languages/markdown/variaveis.md

[Url_HTML_CSS]: https://github.com/Otakubb/lang-anot/tree/main/languages/html-css

[Url_JS]: https://github.com/Otakubb/lang-anot/tree/main/languages/javascript
```

## Dicas:

- `Variáveis no Markdown`