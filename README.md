# Resolução dos desafios do curso de lógica de programação

Praticar lógica de programação, incluindo variáveis, condicionais, loops e interações com o usuário, é crucial para uma carreira em desenvolvimento de software. Esses fundamentos ajudam a resolver problemas de forma estruturada, 
tomar decisões no código, criar iterações controladas e interagir eficazmente com os usuários. Entender esses conceitos facilita o aprendizado de novas tecnologias, 
permite criar soluções inovadoras, depurar código e manter a qualidade do software. Investir nesses princípios desde cedo é essencial para construir uma base sólida na programação.

#### Desafios - Respostas

1) Crie um contador que comece em 1 e vá até 10 usando um loop while. Mostre cada número.

```js
let contador = 1;

while (contador < 10) {
  console.log('Numero ' + contador);
  contador = contador + 1;
}
```

2) Crie um contador que comece em 10 e vá até 0 usando um loop while. Mostre cada número.

```js
let contador = 10;

while (contador >= 0) {
  console.log(contador);
  contador--;
}
```

3) Crie um programa de contagem regressiva. Peça um número ao usuario e conte deste número até 0, usando um loop while no console do navegador.

```js
let numero = prompt("Contagem regressiva:");

while (numero >= 0) {
    console.log(numero);
    numero--;
}

```

4) Crie um programa de contagem progressiva. Peça um número ao usuario e conte de `0` até esté número, usando um loop while no console do navegador.

```js
let numero = prompt("Contagem progressiva");

let contador = 0
while (contador <= numero) {
    console.log(contador);
    contador++;
}
```
