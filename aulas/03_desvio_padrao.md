### 📊 **Conceitos Básicos de Estatística**

| Conceito              | Definição                                                                 | Exemplo                                                                 |
|-----------------------|---------------------------------------------------------------------------|-------------------------------------------------------------------------|
| **População**         | Conjunto total de elementos que estudamos.                                | Todos os alunos de uma escola.                                          |
| **Amostra**           | Parte da população selecionada para análise.                              | 30 alunos escolhidos aleatoriamente.                                   |
| **Parâmetro**         | Medida que descreve uma característica da **população**.                  | A média de altura de todos os alunos da escola.                        |
| **Estatística (estimador)** | Medida calculada a partir de uma **amostra**.                        | A média da altura dos 30 alunos da amostra.                            |
| **Variável**          | Característica medida ou observada.                                       | Altura (quantitativa), cor dos olhos (qualitativa).                    |
| **Tipos de Variáveis**| Classificação das variáveis: **qualitativas** (categorias) ou **quantitativas** (números). | Cor dos olhos (qualitativa), idade (quantitativa).            |
| **Frequência Absoluta**| Número de vezes que um valor aparece em um conjunto de dados.            | Nota 10 apareceu 5 vezes.                                               |
| **Frequência Relativa**| Proporção ou porcentagem de ocorrência de um valor.                      | Nota 10 apareceu em 5 de 20 alunos → 25%.                              |
| **Média**             | Soma dos valores dividida pela quantidade.                                | Dados: [1,65, 1,70, 1,75] → Média = (1,65 + 1,70 + 1,75)/3 = 1,70       |
| **Mediana**           | Valor central em dados ordenados.                                         | Dados: [1,65, 1,70, 1,75] → Mediana = 1,70                             |
| **Moda**              | Valor que mais se repete.                                                 | Dados: [1,70, 1,75, 1,75] → Moda = 1,75                                |
| **Variância**         | Média dos quadrados dos desvios em relação à média.                       | Serve de base para o cálculo do desvio padrão.                         |
| **Desvio Padrão**     | Mede o grau de variação dos dados em relação à média.                     | Pequeno desvio → dados próximos da média; grande desvio → dados dispersos. |

---

## 🌤️ Exemplo Prático: Desvio Padrão nas Temperaturas

Vamos analisar as temperaturas registradas durante **7 dias** em uma cidade com **clima estável**.

### Dados:
**[22, 23, 22, 21, 22, 23, 22] (em ºC)**

---

## 🧮 Passo a Passo

### 1️⃣ Calcule a média (x̄)

> x̄ = (22 + 23 + 22 + 21 + 22 + 23 + 22) ÷ 7  
> x̄ = 155 ÷ 7 ≈ **22,14 ºC**

---

### 2️⃣ Calcule os desvios ao quadrado (xᵢ − x̄)²

| Dia | Temperatura | (xᵢ − x̄)²           |
|-----|-------------|----------------------|
| 1   | 22          | (22 − 22,14)² = 0,02 |
| 2   | 23          | (23 − 22,14)² = 0,74 |
| 3   | 22          | (22 − 22,14)² = 0,02 |
| 4   | 21          | (21 − 22,14)² = 1,30 |
| 5   | 22          | (22 − 22,14)² = 0,02 |
| 6   | 23          | (23 − 22,14)² = 0,74 |
| 7   | 22          | (22 − 22,14)² = 0,02 |

---

### 3️⃣ Some os quadrados dos desvios

> Soma: 0,02 + 0,74 + 0,02 + 1,30 + 0,02 + 0,74 + 0,02 = **2,86**

---

### 4️⃣ Calcule a variância

> Variância (s²) = 2,86 ÷ (7 − 1) = 2,86 ÷ 6 = **0,48**

---

### 5️⃣ Calcule o desvio padrão

> s = √0,48 ≈ **0,69**

---

## ✅ Resultado Final:

**Desvio padrão das temperaturas ≈ 0,69 ºC**

---

## 🧠 Interpretação:

- 📉 **Desvio pequeno (0,69)** → As temperaturas **variaram pouco**.  
- Isso indica que a cidade tem um **clima estável** naquela semana.  

Se os valores fossem muito diferentes (como 5, 10, 15...), o desvio seria maior, indicando **alta variação** (clima instável).

---

---

✏️ **Resumo:**  
O **desvio padrão** ajuda a responder perguntas como:

> _"As temperaturas estão estáveis ou variando muito?"_

E isso vale para notas, alturas, idades e qualquer outro tipo de dado numérico.

### 🧭 Como interpretar os valores do desvio padrão:

| Desvio Padrão (σ) | Interpretação                     |
|-------------------|------------------------------------|
| **0 a 1,5 ºC**     | 🔹 **Clima estável** (baixa variação) |
| **1,5 a 4 ºC**     | ⚠️ **Variação moderada**              |
| **Acima de 4 ºC**  | 🔥 **Clima instável** (alta variação) |

---

Fonte: https://brasilescola.uol.com.br/matematica/desvio-padrao.htm
