# Teste_Target

## Índice

- **Cálculo da Soma**
- **Sequência de Fibonacci**
- **Análise de Faturamento Diário**
- **Percentual de Representação por Estado**
- **Inversão de String**

# 

```
Cálculo da Soma
int INDICE = 13, SOMA = 0, K = 0;
while (K < INDICE) {
    K = K + 1;
    SOMA = SOMA + K;
}
printf("%d", SOMA);

Ao final do processamento, o valor da variável SOMA será 91.

Sequência de Fibonacci
Dada a sequência de Fibonacci, onde se inicia por 0 e 1 e o próximo valor sempre será a soma dos 2 valores anteriores (exemplo: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34…), escreva um programa na linguagem que desejar onde, informado um número, ele calcule a sequência de Fibonacci e retorne uma mensagem avisando se o número informado pertence ou não à sequência.

IMPORTANTE: Esse número pode ser informado através de qualquer entrada de sua preferência ou pode ser previamente definido no código.

Análise de Faturamento Diário
Dado um vetor que guarda o valor de faturamento diário de uma distribuidora, faça um programa, na linguagem que desejar, que calcule e retorne:

O menor valor de faturamento ocorrido em um dia do mês;
O maior valor de faturamento ocorrido em um dia do mês;
Número de dias no mês em que o valor de faturamento diário foi superior à média mensal.
IMPORTANTE: a) Usar o JSON ou XML disponível como fonte dos dados do faturamento mensal; b) Podem existir dias sem faturamento, como nos finais de semana e feriados. Estes dias devem ser ignorados no cálculo da média.

Percentual de Representação por Estado
Dado o valor de faturamento mensal de uma distribuidora, detalhado por estado:

SP – R$67.836,43
RJ – R$36.678,66
MG – R$29.229,88
ES – R$27.165,48
Outros – R$19.849,53
Escreva um programa na linguagem que desejar onde calcule o percentual de representação que cada estado teve dentro do valor total mensal da distribuidora.

Inversão de String
Escreva um programa que inverta os caracteres de uma string.

IMPORTANTE: a) Essa string pode ser informada através de qualquer entrada de sua preferência ou pode ser previamente definida no código; b) Evite usar funções prontas, como, por exemplo, reverse.
