# Calculadora TMB (Taxa Metabólica Basal)

A **Calculadora TMB** é um programa em Python que calcula a Taxa Metabólica Basal (TMB) de uma pessoa, que é a quantidade mínima de calorias que o corpo necessita para manter suas funções vitais em repouso.

## Como funciona?

O cálculo da TMB é realizado com base em informações fornecidas pelo usuário, como:

- **Sexo** (H para Homem, M para Mulher)
- **Peso** (em KG)
- **Idade**
- **Altura** (em cm)

A calculadora utiliza as seguintes fórmulas para calcular a TMB:

- Para **Homens**:
  ```text
  TMB = 66.47 + (13.75 * peso) + (5.003 * altura) - (6.755 * idade)

- Para **Mulheres**:
  ```text
  TMB = 655.09 + (9.563 * peso) + (1.85 * altura) - (4.676 * idade)

