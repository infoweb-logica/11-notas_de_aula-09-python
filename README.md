# Notas de aula de 2026.1.11 - Python - Estrutura de repetição com for

## Informações gerais

- **Público alvo**: alunos da disciplina de **Introdução a lógica e programação** do curso de [Infoweb](https://diatinf.ifrn.edu.br/cursos/tecnico-em-informatica-para-internet/) na [DIATINF](https://diatinf.ifrn.edu.br/) no [CNAT-IFRN](https://portal.ifrn.edu.br/campus/natalcentral/)
- **Professor**: [L A Minora](https://github.com/leonardo-minora/)
- **Objetivo**:
  1. Mostrar a alternativa `for` como estrutura de repetição

---
## Notas de aula [slides pdf](/09-repeticao-for.pdf)
1. Instrução `for`
   - É uma instrução que itera (percorre) os elementos de uma sequência (string ou lista).
   - Realiza uma iteração (repetição) em seu bloco de código para cada elemento presente na sequência.

**Exemplos**
```python
# percorrendo um texto

texto = "isto é um texto"
for caractere in texto:
  print(caractere)

```

```python
# contador com o range

for contador in range(10):
  print(contador)

inicio = 1
fim = 10
for contador in range(inicio, fim)
  print(contador)

inicio = 1
fim = 10
passo = 2
for contador in range(inicio, fim, passo)
  print(contador)

```

---

## Exercícios [Lista de exercícios](/lista.md)
1. Qual é a saída de cada um dos programas a seguir?
```python
## código a
for i in range(7):
  print(i)

``` 
```python
## código b
for i in range(2,17,3):
  print(i)

``` 

2. Usando a instrução for, escreva um programa que tem como entrada um número inteiro positivo n e imprime os números inteiros de 1 a n.

| Exemplo de entrada | Exemplo de saída |
| ------------------ | ---------------- |
| 3                  | 1<br />2<br />3  |
| 6                  | 1<br />2<br />3<br />4<br />5<br />6 |

3. Usando a instrução for, escreva um programa que tem como entrada um número inteiro positivo n e imprime os números inteiros compreendidos no intervalo [-n; n].

| Exemplo de entrada | Exemplo de saída |
| ------------------ | ---------------- |
| 2                  | -2<br />-1<br />0<br />1<br />2 |
| 1                  | -1<br />0<br />1 |

4. Usando a instrução for, escreva um programa que tem como entrada um número inteiro positivo n e imprime os números pares compreendidos no intervalo [2; n].

| Exemplo de entrada | Exemplo de saída |
| ------------------ | ---------------- |
| 6                  | 2<br />4<br />6  |
| 9                  | 2<br />4<br />6<br />8 |

5. Usando a instrução for, escreva um programa que tem como entrada uma string e imprime a quantidade de vogais (a, e, i, o, u) presentes na string.

| Exemplo de entrada | Exemplo de saída |
| ------------------ | ---------------- |
| casa               | 2                |
| pipoca             | 3                |
| BMX                | 0                |
| Acre               | 2                |
