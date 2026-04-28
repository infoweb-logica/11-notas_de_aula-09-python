# Exercícios — Estruturas de Repetição com `for` em Python

> **Público alvo**: alunos da disciplina de Introdução a Lógica e Programação  
> **Objetivo**: praticar o uso de `for` para resolver problemas de programação  

---

## Parte 1 — Estruturas de Repetição com `for`

> Nos exercícios abaixo, utilize **apenas** a instrução `for` para controlar a repetição.

---

**1.** Escreva um programa que imprime os números inteiros de 1 a 10.

**2.** Escreva um programa que imprime os números inteiros de 10 a 1 (em ordem decrescente).

**3.** Escreva um programa que imprime os números pares de 2 a 20.

**4.** Escreva um programa que imprime os números ímpares de 1 a 19.

**5.** Escreva um programa que imprime os múltiplos de 5 entre 5 e 50.

**6.** Escreva um programa que recebe um número inteiro positivo `n` como entrada e imprime todos os inteiros de 1 a `n`.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 4 | 1<br/>2<br/>3<br/>4 |
| 7 | 1<br/>2<br/>3<br/>4<br/>5<br/>6<br/>7 |

**7.** Escreva um programa que recebe um número inteiro positivo `n` e imprime a soma dos números de 1 a `n`.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 5 | 15 |
| 10 | 55 |

**8.** Escreva um programa que recebe um número inteiro positivo `n` e imprime o produto (fatorial) de 1 × 2 × ... × `n`.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 4 | 24 |
| 5 | 120 |

**9.** Escreva um programa que lê 5 números inteiros digitados pelo usuário e imprime a soma deles.

**10.** Escreva um programa que lê 10 números reais digitados pelo usuário e imprime a média aritmética.

**11.** Escreva um programa que recebe um número inteiro positivo `n` e imprime a tabuada de multiplicação de `n` (de 1 a 10).

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 3 | 3 x 1 = 3<br/>3 x 2 = 6<br/>...<br/>3 x 10 = 30 |

**12.** Escreva um programa que imprime todos os números inteiros no intervalo `[-5, 5]`.

**13.** Escreva um programa que recebe um número inteiro positivo `n` e imprime os múltiplos de 3 entre 1 e `n`.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 10 | 3<br/>6<br/>9 |
| 15 | 3<br/>6<br/>9<br/>12<br/>15 |

**14.** Escreva um programa que recebe um número inteiro `base` e um número inteiro positivo `expoente`, e calcula `base ** expoente` **sem usar o operador `**`** — use apenas multiplicações repetidas com `for`.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| base=2, expoente=8 | 256 |
| base=3, expoente=4 | 81 |

**15.** Escreva um programa que lê números inteiros do usuário **enquanto** o usuário não digitar `0`, e ao final exibe a quantidade de números lidos (sem contar o zero).

**16.** Escreva um programa que lê números reais do usuário **enquanto** o usuário não digitar um número negativo, e ao final exibe a soma de todos os valores lidos (sem incluir o negativo).

**17.** Escreva um programa que recebe dois inteiros positivos `a` e `b` (com `a < b`) e imprime todos os inteiros no intervalo `[a, b]`.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| a=3, b=7 | 3<br/>4<br/>5<br/>6<br/>7 |

**18.** Escreva um programa que imprime os primeiros 15 termos da sequência: 1, 3, 5, 7, 9, ...

**19.** Escreva um programa que imprime os primeiros `n` termos da progressão aritmética com primeiro termo `a` e razão `r`, onde `n`, `a` e `r` são fornecidos pelo usuário.

**20.** Escreva um programa que calcula e exibe a soma: 1 + 1/2 + 1/3 + 1/4 + ... + 1/n, onde `n` é fornecido pelo usuário.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 4 | 2.0833333333333335 |

**21.** Escreva um programa que lê `n` notas de alunos (onde `n` é fornecido pelo usuário) e exibe a maior nota lida.

**22.** Escreva um programa que lê `n` notas de alunos (onde `n` é fornecido pelo usuário) e exibe a menor nota lida.

**23.** Escreva um programa que imprime os quadrados perfeitos menores ou iguais a 100 (ou seja, 1, 4, 9, 16, ..., 100).

**24.** Escreva um programa que recebe um número inteiro positivo `n` e exibe a soma dos dígitos de `n`.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 1234 | 10 |
| 305 | 8 |

**25.** Escreva um programa que recebe um número inteiro positivo `n` e exibe `n` na ordem inversa dos dígitos.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 1234 | 4321 |
| 305 | 503 |

---

## Parte 2 — Estruturas de Repetição e Seleção com `for` + `if`

> Nos exercícios abaixo, utilize a instrução `for` para controlar a repetição e `if` / `elif` / `else` para as decisões.

---

**26.** Escreva um programa que imprime os números de 1 a 20 e, ao lado de cada número, escreve `"par"` se o número for par ou `"ímpar"` se for ímpar.

**27.** Escreva um programa que lê 10 números inteiros e exibe quantos são positivos, quantos são negativos e quantos são iguais a zero.

**28.** Escreva um programa FizzBuzz: imprima os inteiros de 1 a 30, mas substitua:
- os múltiplos de `3` pela palavra `Fizz`,
- os múltiplos de `5` pela palavra `Buzz`,
- os múltiplos de `3` **e** `5` pela palavra `FizzBuzz`.

**29.** Escreva um programa que lê `n` números reais e exibe separadamente a soma dos valores positivos e a soma dos valores negativos.

**30.** Escreva um programa que recebe um número inteiro positivo `n` e verifica se ele é primo.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 7 | 7 é primo |
| 9 | 9 não é primo |

**31.** Escreva um programa que lê 10 notas (de 0 a 10) e exibe:
- a média das notas,
- a quantidade de alunos aprovados (média ≥ 7),
- a quantidade de alunos reprovados (média < 5),
- a quantidade de alunos em recuperação (5 ≤ média < 7).

**32.** Escreva um programa que recebe um número inteiro `n` e exibe todos os divisores de `n`.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 12 | 1<br/>2<br/>3<br/>4<br/>6<br/>12 |

**33.** Escreva um programa que lê números inteiros **enquanto** o usuário não digitar `0`, e ao final exibe a soma dos números pares e a soma dos números ímpares lidos.

**34.** Escreva um programa que recebe dois inteiros positivos `a` e `b` e calcula o Máximo Divisor Comum (MDC) usando o algoritmo de Euclides com `for`.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| a=12, b=8 | 4 |
| a=15, b=25 | 5 |

**35.** Escreva um programa que imprime os primeiros `n` números da sequência de Fibonacci, onde `n` é fornecido pelo usuário.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 8 | 0 1 1 2 3 5 8 13 |

**36.** Escreva um programa que lê uma senha digitada pelo usuário e continua pedindo a senha **enquanto** ela estiver incorreta. A senha correta é `"python123"`. Ao acertar, exibe `"Acesso permitido"`.

**37.** Escreva um programa que recebe um inteiro positivo `n` e exibe o número de dígitos de `n`.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 1234 | 4 |
| 50 | 2 |

**38.** Escreva um programa que lê `n` números inteiros e exibe o maior e o menor valor lido.

**39.** Escreva um programa que simula um menu com as opções:
```
1 - Somar dois números
2 - Subtrair dois números
3 - Sair
```
O programa deve repetir o menu **enquanto** o usuário não escolher a opção `3`.

**40.** Escreva um programa que recebe um inteiro positivo `n` e determina se `n` é um número perfeito (um número é perfeito se a soma de seus divisores próprios é igual a ele mesmo, ex: 6 = 1+2+3).

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 6 | 6 é perfeito |
| 28 | 28 é perfeito |
| 10 | 10 não é perfeito |

**41.** Escreva um programa que lê `n` pares de números inteiros `(a, b)` e, para cada par, informa qual é o maior, qual é o menor, ou se são iguais.

**42.** Escreva um programa que recebe um inteiro positivo `n` e exibe todos os números no intervalo `[1, n]` que são simultaneamente divisíveis por 2 e por 7.

**43.** Escreva um programa que lê números inteiros positivos do usuário **enquanto** o usuário não digitar um valor negativo, e ao final exibe quantos dos números lidos são pares e quantos são ímpares.

**44.** Escreva um programa que imprime uma escada de `n` degraus usando o caractere `*`. Cada degrau `i` tem `i` asteriscos.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 4 | `*`<br/>`**`<br/>`***`<br/>`****` |

**45.** Escreva um programa que recebe dois inteiros `inicio` e `fim` e exibe a soma de todos os números primos no intervalo `[inicio, fim]`.

**46.** Escreva um programa que lê `n` números reais e classifica cada um como:
- `"pequeno"` se o valor for menor que 10,
- `"médio"` se o valor estiver entre 10 e 100 (inclusive),
- `"grande"` se o valor for maior que 100.

Ao final, exibe a contagem de cada categoria.

**47.** Escreva um programa que simula um jogo de adivinhação: o programa sorteia um número inteiro entre 1 e 100 e o usuário tenta adivinhar. A cada tentativa o programa informa se o chute foi `"muito baixo"`, `"muito alto"` ou `"acertou!"`. O laço termina quando o usuário acertar.

> Dica: use `import random` e `random.randint(1, 100)` para sortear o número.

**48.** Escreva um programa que recebe um inteiro positivo `n` e verifica se ele é um palíndromo numérico (lê-se igual de trás para frente).

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 121 | 121 é palíndromo |
| 123 | 123 não é palíndromo |

**49.** Escreva um programa que lê `n` valores inteiros e exibe, ao final:
- a soma total,
- a média,
- o maior valor,
- o menor valor,
- a quantidade de valores acima da média.

**50.** Escreva um programa que exibe a seguinte tabela de conversão de temperaturas de 0 °C a 100 °C, de 10 em 10 graus, mostrando Celsius, Fahrenheit e Kelvin. Ao lado de cada linha, classifique a temperatura como `"fria"` (< 15 °C), `"agradável"` (15 °C a 25 °C) ou `"quente"` (> 25 °C).

| Celsius | Fahrenheit | Kelvin | Classificação |
| ------- | ---------- | ------ | ------------- |
| 0 | 32.0 | 273.15 | fria |
| 10 | 50.0 | 283.15 | fria |
| ... | ... | ... | ... |

> Fórmulas: F = C × 9/5 + 32 ; K = C + 273.15

---
