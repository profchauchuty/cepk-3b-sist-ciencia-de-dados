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

## Exemplos

## Exemplo 1: Temperaturas com pouca variação

| Dia | Temperatura (ºC) | Cálculo (xᵢ − x̄)²          |
|-----|------------------|----------------------------|
| 1   | 22               | (22 − 22,14)² = 0,02       |
| 2   | 23               | (23 − 22,14)² = 0,74       |
| 3   | 22               | (22 − 22,14)² = 0,02       |
| 4   | 21               | (21 − 22,14)² = 1,30       |
| 5   | 22               | (22 − 22,14)² = 0,02       |
| 6   | 23               | (23 − 22,14)² = 0,74       |
| 7   | 22               | (22 − 22,14)² = 0,02       |

| Cálculo                   | Valor           |
|---------------------------|-----------------|
| Soma dos quadrados         | 2,86            |
| Variância (dividir por 6) | 2,86 ÷ 6 = 0,48 |
| Desvio padrão             | √0,48 ≈ 0,69    |

---

## Exemplo 2: Temperaturas com muita variação

| Dia | Temperatura (ºC) | Cálculo (xᵢ − x̄)²          |
|-----|------------------|----------------------------|
| 1   | 15               | (15 − 24)² = 81            |
| 2   | 28               | (28 − 24)² = 16            |
| 3   | 20               | (20 − 24)² = 16            |
| 4   | 30               | (30 − 24)² = 36            |
| 5   | 18               | (18 − 24)² = 36            |
| 6   | 35               | (35 − 24)² = 121           |
| 7   | 22               | (22 − 24)² = 4             |

| Cálculo                   | Valor               |
|---------------------------|---------------------|
| Soma dos quadrados         | 310                 |
| Variância (dividir por 6) | 310 ÷ 6 ≈ 51,67     |
| Desvio padrão             | √51,67 ≈ 7,19       |

---

🎯 **Conclusão:**  
- Desvio padrão ≈ 0,69 indica pouca variação nas temperaturas (clima estável).  
- Desvio padrão ≈ 7,19 indica grande variação, refletindo clima instável.
