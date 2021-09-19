# Listas

## _**Listas Ordenadas**_

~~~HTML
<ol>   <!--tag de criação de lista ordenada (obrigatório o fechamento com </ol>-->
    <li>item 1
    <li>item 2  <!--tag <li> list item sem fechamento obrigatório-->
    <li>item 3
</ol>
~~~

**atributos importantes:**

* Type (Marcadores)

~~~HTML
<ol type="tipo de marcador"> <!--Marcadores:-->

<ol type="I"><!--I,II,III,IV-->
<ol type="a"><!--a,b,c,d-->
<ol type="A"><!--A,B,C-->
<ol type="1"> <!--valor padrão 1,2,3,4-->
~~~

* Start (inicio a comtagem)

~~~HTML
<ol start="5"><!--A lista irá começar no numero 5-->
<ol type="A" start="D"><!--No estilo de letras maiusculas a lista vai começar na letra D-->
~~~

## _**Listas Não Ordenadas**_

~~~HTML
<ul>
    <li>Item
    <li>Item
    <li>Item
<ul>
~~~

**atributos importantes**

*Type (Marcador)

~~~HTML
<ul type="square"><!--Quadrada-->
<ul type="disc"><!--bola  vazia-->
<ul type="circle"><!--Padrão bola preencida-->
~~~

## _**Listas Mistas**_
~~~HTML
<ol>
    <li>Item 1
    <li>Item 2
        <ol>
            <li> Item 2.1
            <li>Item 2.2
        <ol>
<ol>
~~~

#### _**Lista de Definições**_

~~~HTML
<dl>
    <dt>Termo de definição
        <dd>descrição do termo
<dl>
~~~
