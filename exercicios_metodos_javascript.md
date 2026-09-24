# Exercícios de JavaScript — Métodos

Lista de exercícios simples para praticar os métodos apresentados na aula.

> Regra: tente resolver cada exercício usando o método indicado no comentário. Não altere a estrutura inicial do exercício.

---

## 01. Achatar um array com `flat()`

```js
const array = [1, [2, [3, [4]]], 5];

export function achatarArray(array) {

  // Use o método flat()
  // O objetivo é remover os níveis internos do array.
  // Resultado esperado: [1, 2, 3, 4, 5]

}

achatarArray(array);
```

---

## 02. Dobrar os números com `map()`

```js
const numeros = [1, 2, 3, 4, 5];

export function dobrarNumeros(numeros) {

  // Use o método map()
  // Multiplique cada número por 2.
  // Resultado esperado: [2, 4, 6, 8, 10]

}

dobrarNumeros(numeros);
```

---

## 03. Criar uma lista de nomes em maiúsculas com `map()`

```js
const nomes = ["ana", "carlos", "joao", "maria"];

export function formatarNomes(nomes) {

  // Use map() para percorrer todos os nomes.
  // Use toUpperCase() para transformar cada nome em maiúsculas.
  // Resultado esperado: ["ANA", "CARLOS", "JOAO", "MARIA"]

}

formatarNomes(nomes);
```

---

## 04. Filtrar números pares com `filter()`

```js
const numeros = [1, 2, 3, 4, 5, 6, 7, 8];

export function filtrarPares(numeros) {

  // Use o método filter()
  // Mantenha somente os números pares.
  // Resultado esperado: [2, 4, 6, 8]

}

filtrarPares(numeros);
```

---

## 05. Encontrar um produto com `find()`

```js
const produtos = [
  { id: 1, nome: "Teclado" },
  { id: 2, nome: "Mouse" },
  { id: 3, nome: "Monitor" }
];

export function encontrarProduto(produtos) {

  // Use o método find()
  // Encontre o produto cujo id seja 2.
  // Resultado esperado: { id: 2, nome: "Mouse" }

}

encontrarProduto(produtos);
```

---

## 06. Encontrar a posição com `indexOf()`

```js
const linguagens = ["HTML", "CSS", "JavaScript", "React"];

export function encontrarPosicao(linguagens) {

  // Use indexOf()
  // Descubra a posição de "JavaScript".
  // Resultado esperado: 2

}

encontrarPosicao(linguagens);
```

---

## 07. Somar valores com `reduce()`

```js
const numeros = [10, 20, 30, 40];

export function somarNumeros(numeros) {

  // Use reduce()
  // Some todos os números do array.
  // Resultado esperado: 100

}

somarNumeros(numeros);
```

---

## 08. Calcular o total de produtos com `reduce()`

```js
const precos = [29.90, 10.50, 50.00, 15.00];

export function calcularTotal(precos) {

  // Use reduce()
  // Some todos os preços.
  // Resultado esperado: 105.40

}

calcularTotal(precos);
```

---

## 09. Verificar se todos são maiores de idade com `every()`

```js
const idades = [18, 21, 25, 30];

export function verificarIdades(idades) {

  // Use every()
  // Verifique se todas as idades são maiores ou iguais a 18.
  // Resultado esperado: true

}

verificarIdades(idades);
```

---

## 10. Ordenar números com `sort()`

```js
const numeros = [10, 2, 8, 1, 5];

export function ordenarNumeros(numeros) {

  // Use sort()
  // Ordene os números do menor para o maior.
  // Lembre-se de usar uma função de comparação numérica.
  // Resultado esperado: [1, 2, 5, 8, 10]

}

ordenarNumeros(numeros);
```

---

## 11. Encontrar o maior número com `Math.max()`

```js
const numeros = [10, 45, 23, 89, 12];

export function encontrarMaior(numeros) {

  // Use Math.max()
  // Utilize o spread operator (...) para passar os valores do array.
  // Resultado esperado: 89

}

encontrarMaior(numeros);
```

---

## 12. Encontrar o menor número com `Math.min()`

```js
const numeros = [10, 45, 23, 89, 12];

export function encontrarMenor(numeros) {

  // Use Math.min()
  // Utilize o spread operator (...) para passar os valores do array.
  // Resultado esperado: 10

}

encontrarMenor(numeros);
```

---

## 13. Transformar uma frase em array com `split()`

```js
const frase = "JavaScript é muito legal";

export function separarPalavras(frase) {

  // Use split()
  // Separe a frase utilizando o espaço como separador.
  // Resultado esperado:
  // ["JavaScript", "é", "muito", "legal"]

}

separarPalavras(frase);
```

---

## 14. Substituir uma palavra com `replace()`

```js
const frase = "Eu estou aprendendo Java";

export function corrigirFrase(frase) {

  // Use replace()
  // Substitua "Java" por "JavaScript".
  // Resultado esperado:
  // "Eu estou aprendendo JavaScript"

}

corrigirFrase(frase);
```

---

## 15. Juntar palavras com `join()`

```js
const palavras = ["JavaScript", "é", "uma", "linguagem"];

export function juntarPalavras(palavras) {

  // Use join()
  // Junte todas as palavras utilizando um espaço.
  // Resultado esperado:
  // "JavaScript é uma linguagem"

}

juntarPalavras(palavras);
```

---

## 16. Converter um número para texto com `toString()`

```js
const numero = 12345;

export function converterParaTexto(numero) {

  // Use toString()
  // Converta o número para uma string.
  // Resultado esperado:
  // "12345"

}

converterParaTexto(numero);
```

---

## 17. Transformar texto em minúsculas com `toLowerCase()`

```js
const email = "ALUNO@EMAIL.COM";

export function normalizarEmail(email) {

  // Use toLowerCase()
  // Transforme todo o e-mail em letras minúsculas.
  // Resultado esperado:
  // "aluno@email.com"

}

normalizarEmail(email);
```

---

## 18. Transformar texto em maiúsculas com `toUpperCase()`

```js
const estado = "sp";

export function formatarEstado(estado) {

  // Use toUpperCase()
  // Transforme a sigla para letras maiúsculas.
  // Resultado esperado:
  // "SP"

}

formatarEstado(estado);
```

---

## 19. Usar `flatMap()`

```js
const numeros = [1, 2, 3];

export function duplicarEExpandir(numeros) {

  // Use flatMap()
  // Para cada número, retorne o número original e o dobro dele.
  // Resultado esperado:
  // [1, 2, 2, 4, 3, 6]

}

duplicarEExpandir(numeros);
```

---

## 20. Desafio final: combinar vários métodos

```js
const produtos = [
  { nome: "Teclado", preco: 80 },
  { nome: "Mouse", preco: 30 },
  { nome: "Monitor", preco: 500 },
  { nome: "Fone", preco: 100 }
];

export function processarProdutos(produtos) {

  // Etapa 1:
  // Use filter() para manter somente produtos com preço maior que 50.

  // Etapa 2:
  // Use map() para aplicar 10% de desconto no preço.

  // Etapa 3:
  // Use sort() para ordenar os produtos pelo preço, do menor para o maior.

  // Resultado esperado:
  // [
  //   { nome: "Teclado", preco: 72 },
  //   { nome: "Fone", preco: 90 },
  //   { nome: "Monitor", preco: 450 }
  // ]

}

processarProdutos(produtos);
```

---

# Desafio extra

Tente resolver os exercícios novamente sem olhar os comentários.

Depois, explique com suas próprias palavras:

- Para que serve `map()`?
- Qual a diferença entre `filter()` e `find()`?
- Quando usar `reduce()`?
- Qual a diferença entre `split()` e `join()`?
- Quando usar `indexOf()`?
- Qual a diferença entre `flat()` e `flatMap()`?
- Por que precisamos de uma função de comparação no `sort()` para números?

---

# Objetivo da prática

Ao terminar os exercícios, você deverá conseguir identificar qual método usar de acordo com o problema:

```text
Transformar       -> map()
Achatar           -> flat()
Transformar +     -> flatMap()
achatar

Filtrar           -> filter()
Encontrar item    -> find()
Encontrar posição -> indexOf()

Acumular          -> reduce()
Validar todos     -> every()

Ordenar           -> sort()
Maior valor       -> Math.max()
Menor valor       -> Math.min()

Separar texto     -> split()
Substituir texto  -> replace()
Juntar texto      -> join()
Converter texto   -> toString()

Minúsculas        -> toLowerCase()
Maiúsculas        -> toUpperCase()
```

---

LEO GOMES DEVELOPER  
leogomesdev
