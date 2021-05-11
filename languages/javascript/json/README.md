# JSON - JavaScript Object Notation

JSON é uma forma de se escrever objetos em Javascript. Pode ser visto como um formato "universal" que é muito conveniente para troca de informações entre aplicações através de diversos protocolos.

O JSON funciona da seguinte maneira ... 

```JSON
{
  "Chave": "Valor"
}
```

Um outro exemplo:

```JSON
{
  "name": "Feh's"
}
```

## Tipos de Valores

Os valores podem ser, `Strings`, `Booleans`, `Numbers`, `Objects` e `Arrays`...

### Strings

As strings podem guardar todo tipo de informação ... 

Ex:
```json
{
  "Tag": "Feh's#5060"
}
```

### Booleans

Os booleans só podem receber `false/true` (O `boolean` é Case Sensitive, ou seja, se você colocar `False`, vai dar erro porque o `F` está em maiusculo).

Ex:
```json
{
  "UseDiscord": true
}
```

### Numbers

Como o próprio nome diz, ele só recebe numeros, e somente numeros inteiros.

Ex:
```json
{
  "Age": 16
}
```

### Arrays

Os `arrays` funciona da seguinte maneira, imagine uma lista de celulares, uma lista de celulares bem detalhada ...

Ex: 
```
             Lista de Celulares
--------------------------------------------
      Modelos | Color | Qtd | Preço 
Redmi Note 10 | Gray  | 10  | 2.100,00
Redmi Note 9s | Black |  2  | 1.500,00
   Samsung S7 | White |  5  | 1.700,00
Iphone 12 Pro | Purple| 19  | 2.700,00
--------------------------------------------
```

Tá, essa lista possui **celulares** e os respectivos **modelos** ...

```json
{
  "Cells": {
    "Models": []
  }
}
```

Também tem os `Objects`, os `objects` dá para colocar coisas mais detalhadas nela, tipo **Nome**, **Cor**, **Qtd**, **Preço** e assim vai, mas, nós só vamos usar ele para armazenar os **modelos** q será uma `Array`.

> Dica
> Para `Objects` vc usa `{}` e para `Arrays` vc usa `[]`
>
> `"Cells": {}` -> **Object**
> 
> `"Models": []` -> **Array**

Certo agora vamos colocar os celulares:
```json
{
  "Cells": {
    "models": {
      "Redmi Note 10": {
        "Color": "Gray",
        "Qtd": 10,
        "Price": 2100
      },
      "Redmi Note 9s": {
        "Color": "Black",
        "Qtd": 2,
        "Price": 1500
      },
      "Samsung S7": {
        "Color": "White",
        "Qtd": 5,
        "Price": 1700
      },
      "Iphone 12 Pro": {
        "Color": "Purple",
        "Qtd": 19,
        "Price": 2700
      },
    }
  }
}
```

## Outros

[JavaScript][Url_JS]

- `JSON - JavaScript Object Notation`

[Url_JS]: ../README.md

<!-- Urls - Outros - Begin -->

<!-- Urls - Outros - Begin -->