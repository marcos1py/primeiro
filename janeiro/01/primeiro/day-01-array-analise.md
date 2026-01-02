# Day 01 – Análise de Números em um Array (Java)

## Contexto
Você recebeu uma lista de números inteiros representando métricas coletadas ao longo do dia
(por exemplo, tempo de resposta de um sistema).

Seu objetivo é analisar esses dados e extrair informações básicas, porém essenciais.

Esse tipo de problema testa:
- Lógica
- Uso correto de arrays
- Controle de fluxo
- Clareza de código
- Pensamento analítico (muito comum em Big Tech)

---

## Desafio

Implemente um método em Java que receba um array de inteiros e retorne um objeto (ou imprima)
com as seguintes informações:

1. O maior número do array
2. O menor número do array
3. A média dos valores
4. Quantos números são pares
5. Quantos números são ímpares

---

## Regras

- Não use Streams (`stream()`) neste exercício
- Não use bibliotecas externas
- Use apenas:
  - `for`
  - `if`
  - variáveis primitivas
- O método deve lidar com arrays de qualquer tamanho ≥ 1

---

## Assinatura sugerida

```java
public static void analisarNumeros(int[] numeros)
