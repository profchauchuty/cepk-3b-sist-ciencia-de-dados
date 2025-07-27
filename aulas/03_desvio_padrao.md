# 📊 Conceitos Básicos de Estatística

| Conceito       | Definição                                     | Exemplo                                                         |
|----------------|----------------------------------------------|----------------------------------------------------------------|
| **População**  | Conjunto total de elementos que estudamos.  | Todos os alunos de uma escola.                                  |
| **Amostra**    | Parte da população selecionada para análise. | 30 alunos escolhidos aleatoriamente.                            |
| **Variável**   | Característica medida ou observada.          | Altura (quantitativa), cor dos olhos (qualitativa).            |
| **Média**      | Soma dos valores dividida pela quantidade.    | Dados: [1,65, 1,70, 1,75]<br>**Média = (1,65 + 1,70 + 1,75) / 3 = 1,70** |
| **Mediana**    | Valor central em dados ordenados.              | Dados: [1,65, 1,70, 1,75]<br>Mediana = 1,70 (valor do meio)    |
| **Moda**       | Valor que mais se repete.                      | Dados: [1,70, 1,75, 1,75]<br>Moda = 1,75 (mais frequente)      |
| **Desvio Padrão** | Mede a variação dos dados em relação à média.| Pequeno desvio indica dados próximos da média.                  |

---

# Como calcular o Desvio Padrão

O desvio padrão mostra o quanto os dados estão espalhados em torno da média.

---

## Dados:
**[ 1.65, 1.70, 1.75, 1.80, 1.85 ]**

---

## Passo 1: Calcule a média (x̄)
Média (x̄) = Soma dos valores ÷ quantidade de valores  
> x̄ = (x₁ + x₂ + ... + xₙ) ÷ n

**Exemplo:**  
> x̄ = (1,65 + 1,70 + 1,75 + 1,80 + 1,85) ÷ 5 = 1,75

---

## Passo 2: Calcule o quadrado do desvio da média

Quadrado do desvio da média (xᵢ − x̄)²: Para cada valor, calcule (xᵢ − x̄)².

> (1,65 − 1,75)² = 0,01  
> (1,70 − 1,75)² = 0,0025  
> (1,75 − 1,75)² = 0  
> (1,80 − 1,75)² = 0,0025  
> (1,85 − 1,75)² = 0,01

---

## Passo 3: Some todos os resultados

Soma dos quadrados = Σ (xᵢ − x̄)²

**Exemplo:**  
> 0,01 + 0,0025 + 0 + 0,0025 + 0,01 = 0,025

---

## Passo 4: Divida a soma por (n − 1)

Variância (s²) = Soma dos quadrados ÷ (n − 1)

**Exemplo:**  
> s² = 0,025 ÷ (5 − 1) = 0,025 ÷ 4 = 0,00625

---

## Passo 5: Calcule a raiz quadrada do valor

Desvio padrão (s | σ) = √variância

**Exemplo:**  
> s = √0,00625 ≈ 0,079

---

## Resultado final:
🎯 **Desvio padrão (s | σ) ≈ 0,079**

---
