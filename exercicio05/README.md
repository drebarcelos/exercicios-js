# Descrição

  Crie uma função que receba a estrutura
  desse objeto pokemon e imprima na tela
  o seguinte template:

```bash
  Nome: Pikachu - Tipo: Eletric
  Habilidade: Static

  Linha de evolução:
    Pichu >> PIKACHU >> Raichu

  Atributos:

    HP: 100
    ATK: 55 SpATK: 100
    DEF: 34 SpDEF: 30
    SPEED: 150

  Ataques:
    Lv 5 - Tackle
    Lv 9 - Thunder Wave
    Lv 20 - Thunderbolt
    Lv 50 - Thunder
```

### Observações
Map, reduce e filter são métodos de arrays em JavaScript. Cada um deles percorrerá um array e realizará uma transformação ou um cálculo. Eles retornarão um novo array com base no resultado da função.

O método `map()` é usado para criar um novo array a partir de um array existente, aplicando uma mesma função a cada um dos elementos do array inicial.
Ex: 
const numeros = [1, 2, 3, 4];
const dobro = numeros.map(numero => numero * 2);

O método `filter()` recebe cada elemento do array e aplica uma instrução condicional a ele. Se essa condição for verdadeira, o elemento é colocado no array de resultado. Se for falsa, o elemento não é colocado lá.
Ex:
const medias = [6.6, 5, 8, 9.5];
const aprovados = medias.filter(media => media >= 6);

O método `sort()` permite ordenar elementos de um array. Além de retornar o array ordenado, altera as posições dos elementos no array original.
Por padrão, o método sort() classifica os elementos do array em ordem crescente, com o menor valor primeiro e o maior por último. Mas ele também aceita um argumento opcional, que pode ser alguma função que compare dois elementos do array.