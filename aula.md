## Linguagem de programação

Maneira de dar instrução ao computador.
Como um lego, vc irá utilizar peças para montar um algoritmo, ou seja, para resolver problemas.

   **Algorítmo**: Sequência de passos lógica e finita para a resolução de um problema.

## Peças de uma linguagem

- [x] Comentários
- Declaração de variáveis (const, let)
  -obs.: let(muda), const(não muda)!
- Operadores (atribuição, concatenação, matemáticos, lógicos)
- Tipos de dados (string, number, boolean)
- Estrutura de dados (functions, object, array)
- Controle de fluxo (if/else)
- Estrutura de repetição (for, while)

## Programar: Resolver problemas através das linhas de código

# Fases da resolução de um problema

- Coletar dados
- Processar os dados (manipular, alterar...)
- Apresentar os dados

## Escopo e variáveis

- [x] Variáveis globais e locais
- [x] Constantes

## Tipos de dados

- [x] Strings (textos): "" '' ``
- [x] Number: 2  1.4
- [x] Function
- [x] Bollean: true, false (Depende se a meta foi completada ou não)!

## Operadores

- [x] Operadores de atribuição de valor (=)
- [x] Operador de concatenação (+), é a junção de 2 ou mais Strings
- [x] Operador de comparação (<, >)  ( == )  ( != )  (<=)  (=>)
- [x] Spread operator: ...

## Estruturas de dados:

### Arrays: Uma lista que contém qualquer tipo de dado

- [x] Métodos de array: push, [find, forEach, filter, map] : HOF (Higher Order Functions)

### Objetos:

- [x] Atributos e métodos
- [x] Criação e manipulação de objetos
- [x] Acesso a propriedades de objetos (.)

### Functions

- [x] criar, passar argumento
- [x] executar
- [x] arrow function, ex.: 
const start = () => {
   console.log('começou')
}
start()

- [x] named function, ex.:
function start() {
   console.log('começou')
}
start()

## count++   =    count = count + 1

## Estruturas de repetição

- [x] while  ex.: 
const start = () => {
    let count = 0 
    while(count <= 10) {
    console.log(count)
    count = count + 1
    }
}
start()

## while(true) , por exemplo, é necessário q haja um return para que a função seja interrompida!


## Condicionais

- [x] switch
- [x] if/else

## Módulos em Node.js

- [x] Importação de módulos (require, CommomJS)
   - Ocorre com a instalação, ex.:  
     npm install inquirer 
   - E a utilização, ex.: 
     const { select } = require('@inquirer/prompts')

- [x] Biblioteca 'inquirer' para criar prompts interativos

- [x] FS (file system)

## JSON
- [x] Javascript Object Notation (.json)
- [x] JSON.parse(): transforma de JSON para JS
- [x] JSON.strigify(): transforma de JS para JSON

## Programação assíncrona e Promises:

- Uso de funções assíncronas (async/await)

## Cada linguagem de programação tem seu maneira de escrita: Sintaxe
