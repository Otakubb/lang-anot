# Midia

## Imagem

~~~HTML
<picture>
    <source media="(max-width: 550px)" type="image/png ou jpeg" srcset="image exmplo 3" >
    <source media="(max-width: 1050px)" srcset="imagem exemplo2" type="image/(jpeg ou png)">
    <img src="imagem" alt="imagem exemplo">
</picture>
~~~
### atributos :
* type="imagem/(png ou jpeg)" - ver no ficheiro [hiperligações.md](https://github.com/Otakubb/lang-anot/blob/main/languages/html-css/CompleteAnot/hiperligações.md)
* media="(max-width:)" - tamanho máximo qu a imagem pode atingir.

     neste atributo existe uma ordem que tem de ser seguida, imaginemos  que se tem 3 imagens, a padrão, uma média e uma pequena. o parametro media tem de ser colocado de forma decrescente de tamanhos, como no exemplo a seguir

     __*Nota*__: _a tag <img.> deve ser colocado em ultimo dentro da tag <picture.>_

* srcset="imagem" - imagem que será carregada quando a anterior 