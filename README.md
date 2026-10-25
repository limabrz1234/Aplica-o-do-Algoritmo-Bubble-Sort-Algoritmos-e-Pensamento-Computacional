# Aplica-o-do-Algoritmo-Bubble-Sort-Algoritmos-e-Pensamento-Computacional
Projeto Bubble Sort - Controle Financeiro
## 1. Identificação

- **Disciplina:** [Algoritmos e Pensamento Computacional]
- **Professora:** [Profa. Karla R. Sartin]
- **Integrante:**
  - [Matheus de Lima Braz]


## 2. Descrição do problema

O controle financeiro é uma atividade importante no cotidiano de pessoas, famílias e empresas. Organizar as despesas ajuda a identificar os maiores gastos e facilita o planejamento do orçamento.

Este projeto apresenta uma aplicação em linguagem C que recebe dez valores de despesas e os organiza do maior para o menor.

## 3. Objetivo

Desenvolver uma aplicação que utilize arrays, estruturas de repetição, condicionais e o algoritmo Bubble Sort para ordenar despesas em ordem decrescente.

## 4. Funcionamento do Bubble Sort

O Bubble Sort compara elementos adjacentes de um array. Neste projeto, quando o valor da esquerda é menor que o valor da direita, os elementos são trocados.

O processo é repetido até que os valores estejam ordenados. O programa também utiliza uma variável de controle para identificar quando não são necessárias novas trocas.

## 5. Requisitos implementados

- Linguagem C.
- Array com dez despesas.
- Leitura de dados informados pelo usuário.
- Validação de valores não negativos.
- Exibição dos dados antes da ordenação.
- Ordenação manual pelo Bubble Sort, sem função pronta de ordenação.
- Exibição dos dados após a ordenação.
- Critério de ordenação decrescente.
- Comentários explicativos no código.

## 6. Como compilar e executar

É necessário ter um compilador C, como o GCC.

### Compilar

```bash
gcc main.c -o controle_financeiro
```

### Executar no Windows

```bash
controle_financeiro.exe
```

### Executar no Linux

```bash
./controle_financeiro
```

Também é possível utilizar um ambiente online compatível com a linguagem C.

## 7. Exemplo de entrada

Informe os seguintes valores, um por vez:

```text
120
45
300
80
150
25
500
60
200
100
```

## 8. Exemplo de saída após a ordenação

```text
--- DESPESAS APOS A ORDENACAO ---
Criterio: ordem decrescente (maior para menor).

1. R$ 500.00
2. R$ 300.00
3. R$ 200.00
4. R$ 150.00
5. R$ 120.00
6. R$ 100.00
7. R$ 80.00
8. R$ 60.00
9. R$ 45.00
10. R$ 25.00
```

## 9. Tecnologias e ferramentas

- Linguagem C.
- GCC ou compilador C equivalente.
- Visual Studio Code e ambiente online.
- GitHub para hospedagem do repositório.

## 10. Considerações finais

O desenvolvimento deste projeto permite aplicar conceitos fundamentais de programação, como arrays, variáveis, estruturas condicionais e laços de repetição.

A implementação do Bubble Sort demonstra como os dados podem ser organizados por meio de comparações e trocas entre elementos adjacentes. A aplicação contribui para a visualização dos maiores gastos e pode auxiliar na organização financeira.
