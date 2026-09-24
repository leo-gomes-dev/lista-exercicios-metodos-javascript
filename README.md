# Exercícios de Métodos JavaScript

Lista de exercícios para praticar os principais métodos de JavaScript apresentados em aula.

O objetivo é aprender a identificar **qual método utilizar para resolver cada problema**, escrevendo o código e testando o resultado.

---

## Conteúdo

Os exercícios trabalham os seguintes métodos:

### Arrays

- `map()`
- `flat()`
- `flatMap()`
- `filter()`
- `find()`
- `indexOf()`
- `reduce()`
- `every()`
- `sort()`

### Matemática

- `Math.max()`
- `Math.min()`

### Strings

- `split()`
- `replace()`
- `join()`
- `toString()`
- `toLowerCase()`
- `toUpperCase()`

---

## Como começar

### 1. Baixe ou clone o projeto

Se o projeto estiver no GitHub:

```bash
git clone URL_DO_PROJETO
```

Depois entre na pasta:

```bash
cd nome-do-projeto
```

---

## 2. Abra o projeto no VS Code

Abra a pasta dos exercícios no Visual Studio Code.

Você pode utilizar:

```bash
code .
```

Ou abrir a pasta diretamente pelo VS Code.

---

## 3. Crie seus arquivos

Cada exercício possui uma estrutura parecida com esta:

```js
const numeros = [1, 2, 3, 4, 5];

export function dobrarNumeros(numeros) {
  // Escreva seu código aqui
}

dobrarNumeros(numeros);
```

Sua tarefa é completar o código dentro da função.

Não altere os dados fornecidos no exercício.

---

# Como pensar antes de programar

Antes de escrever o código, leia o problema e pergunte:

> O que preciso fazer com esses dados?

Use este mapa para ajudar:

| Preciso...                           | Método          |
| ------------------------------------ | --------------- |
| Transformar cada item                | `map()`         |
| Achatar um array                     | `flat()`        |
| Transformar e achatar                | `flatMap()`     |
| Filtrar itens                        | `filter()`      |
| Encontrar um item                    | `find()`        |
| Encontrar uma posição                | `indexOf()`     |
| Somar ou acumular valores            | `reduce()`      |
| Verificar se todos atendem uma regra | `every()`       |
| Ordenar valores                      | `sort()`        |
| Encontrar o maior número             | `Math.max()`    |
| Encontrar o menor número             | `Math.min()`    |
| Separar um texto                     | `split()`       |
| Substituir texto                     | `replace()`     |
| Juntar itens                         | `join()`        |
| Converter para texto                 | `toString()`    |
| Colocar em minúsculas                | `toLowerCase()` |
| Colocar em maiúsculas                | `toUpperCase()` |

---

# Exemplos rápidos

## map()

Use quando precisar transformar todos os elementos.

```js
const numeros = [1, 2, 3];

const resultado = numeros.map((numero) => numero * 2);

console.log(resultado);
```

Resultado:

```js
[2, 4, 6];
```

---

## filter()

Use quando precisar selecionar somente alguns elementos.

```js
const numeros = [1, 2, 3, 4, 5];

const resultado = numeros.filter((numero) => numero > 2);

console.log(resultado);
```

Resultado:

```js
[3, 4, 5];
```

---

## find()

Use quando precisar encontrar um único item.

```js
const numeros = [10, 20, 30];

const resultado = numeros.find((numero) => numero === 20);

console.log(resultado);
```

Resultado:

```js
20;
```

---

## reduce()

Use quando precisar transformar vários valores em um único resultado.

```js
const numeros = [10, 20, 30];

const resultado = numeros.reduce((total, numero) => total + numero, 0);

console.log(resultado);
```

Resultado:

```js
60;
```

---

## split()

Use para transformar um texto em um array.

```js
const frase = 'JavaScript é legal';

const palavras = frase.split(' ');

console.log(palavras);
```

Resultado:

```js
['JavaScript', 'é', 'legal'];
```

---

## join()

Use para transformar um array em um texto.

```js
const palavras = ['JavaScript', 'é', 'legal'];

const frase = palavras.join(' ');

console.log(frase);
```

Resultado:

```text
JavaScript é legal
```

---

# Como testar

Depois de escrever seu código, execute o arquivo usando o ambiente configurado para a aula.

Você também pode testar pequenos exemplos diretamente no console do navegador.

No Chrome:

```text
F12
```

Depois abra a aba:

```text
Console
```

Exemplo:

```js
const numeros = [1, 2, 3];

console.log(numeros.map((numero) => numero * 2));
```

---

# Importante

Não tente decorar todos os métodos.

O mais importante é entender **qual problema cada método resolve**.

Por exemplo:

```text
Quero transformar?
    ↓
  map()

Quero filtrar?
    ↓
 filter()

Quero encontrar?
    ↓
 find()

Quero somar/acumular?
    ↓
 reduce()

Quero ordenar?
    ↓
 sort()
```

---

# Ordem recomendada

Faça os exercícios nesta ordem:

1. `map()`
2. `flat()`
3. `flatMap()`
4. `filter()`
5. `find()`
6. `indexOf()`
7. `reduce()`
8. `every()`
9. `sort()`
10. `Math.max()`
11. `Math.min()`
12. `split()`
13. `replace()`
14. `join()`
15. `toString()`
16. `toLowerCase()`
17. `toUpperCase()`
18. Desafio final

---

# Desafio final

No final da lista existe um exercício que combina vários métodos.

Você deverá trabalhar com produtos:

```js
const produtos = [
  { nome: 'Teclado', preco: 80 },
  { nome: 'Mouse', preco: 30 },
  { nome: 'Monitor', preco: 500 },
  { nome: 'Fone', preco: 100 },
];
```

O exercício pede para:

```text
1. Filtrar produtos acima de R$ 50
2. Aplicar 10% de desconto
3. Ordenar pelo preço
```

Métodos sugeridos:

```js
filter();
map();
sort();
```

Tente resolver sozinho antes de procurar uma solução.

---

# Dica para os exercícios

Quando encontrar um exercício difícil:

1. Leia o enunciado novamente.
2. Identifique o que precisa acontecer com os dados.
3. Escolha o método adequado.
4. Faça um exemplo pequeno.
5. Use `console.log()` para verificar o resultado.
6. Só depois tente melhorar o código.

Exemplo:

```js
console.log(resultado);
```

O `console.log()` será seu principal aliado durante os exercícios.

---

# Regra principal

Não copie a solução.

Primeiro tente resolver.

Se não conseguir:

```text
1ª tentativa → tente sozinho
2ª tentativa → revise a aula
3ª tentativa → consulte a documentação
4ª tentativa → peça ajuda
```

O objetivo não é terminar rapidamente.

O objetivo é aprender a **pensar como um desenvolvedor**.

---

## Projeto

**Exercícios de Métodos JavaScript**

### Instrutor

**LEO GOMES DEVELOPER**

leogomesdev
