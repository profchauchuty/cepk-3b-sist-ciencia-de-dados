### 📊 **Conceitos Básicos de Estatística**

| Conceito              | Definição                                                                 | Exemplo                                                                 |
|-----------------------|---------------------------------------------------------------------------|-------------------------------------------------------------------------|
| **População**         | Conjunto total de elementos que estudamos.                                | Temperaturas registradas durante os 30 dias de um mês.                 |
| **Amostra**           | Parte da população selecionada para análise.                              | Temperaturas de apenas 7 dias do mês.                                  |
| **Parâmetro**         | Medida que descreve uma característica da **população**.                  | Média de temperatura dos 30 dias do mês.                               |
| **Estatística (estimador)** | Medida calculada a partir de uma **amostra**.                        | Média de temperatura dos 7 dias escolhidos.                            |
| **Variável**          | Característica medida ou observada.                                       | Temperatura registrada diariamente (quantitativa).                     |
| **Tipos de Variáveis**| Classificação das variáveis: **qualitativas** (categorias) ou **quantitativas** (números). | Temperatura (quantitativa), condição climática (qualitativa). |
| **Frequência Absoluta**| Número de vezes que um valor aparece em um conjunto de dados.            | Temperatura 22 ºC apareceu 10 vezes.                                   |
| **Frequência Relativa**| Proporção ou porcentagem de ocorrência de um valor.                      | 22 ºC apareceu em 10 de 30 dias → 33,3%.                               |
| **Média**             | Soma dos valores dividida pela quantidade.                                | Média de temperaturas de 30 dias.                                      |
| **Mediana**           | Valor central em dados ordenados.                                         | Temperatura do 15º e 16º dia (em 30 dias ordenados).                   |
| **Moda**              | Valor que mais se repete.                                                 | Temperatura que mais apareceu no mês.                                  |
| **Variância**         | Média dos quadrados dos desvios em relação à média.                       | Usada para calcular o desvio padrão.                                   |
| **Desvio Padrão**     | Mede o grau de variação dos dados em relação à média.                     | Quanto as temperaturas variaram no mês.                                |
| **Ajuste de Bessel**  | Correção usada na variância amostral que divide pela quantidade de dados menos 1 (n − 1), para evitar subestimar a variabilidade da população. | Garante que a variância calculada a partir da amostra seja uma estimativa mais precisa da variância real da população. |

---

## 🌡️ Exemplo 1 - Clima: População (30 dias)

### Fórmula - Desvio Padrão Populacional:

> σ² = (1 / N) × Σ (xᵢ − μ)

> σ = √(σ²)


### Dados (ºC):
[22, 22, 23, 22, 21, 22, 23, 22, 21, 22, 22, 23, 21, 22, 22, 21, 22, 23, 22, 21, 23, 22, 22, 22, 22, 23, 22, 21, 22, 23]

### 1️⃣ Média:
> x̄ = (Soma dos valores) ÷ 30  
> x̄ = 660 ÷ 30 = **22,00 ºC**

### 2️⃣ Desvios ao quadrado (xᵢ − x̄)²:
| Temperatura | Desvio (xᵢ − x̄) | (xᵢ − x̄)² |
|-------------|------------------|-------------|
| 22          | 0                | 0           |
| 23          | 1                | 1           |
| 21          | -1               | 1           |
| ...         | ...              | ...         |

Valores 23 → 7 vezes → 7 × 1 = 7  
Valores 22 → 18 vezes → 18 × 0 = 0  
Valores 21 → 5 vezes → 5 × 1 = 5

**Soma total dos desvios² = 12**

### 3️⃣ Variância (populacional):
> σ² = 12 ÷ 30 = **0,40**

### 4️⃣ Desvio padrão:
> σ = √0,40 ≈ **0,63 ºC**

---

## 🌡️ Exemplo 2 - Clima: Amostra (7 dias)

### Fórmula - Desvio Padrão Populacional:

> σ² = (1 / (N - 1)) × Σ (xᵢ − μ)

> s = √(s²)

### Dados (ºC):  
[22, 23, 22, 21, 22, 23, 22]

### 1️⃣ Média:
> x̄ = (22 + 23 + 22 + 21 + 22 + 23 + 22) ÷ 7 = 155 ÷ 7 ≈ **22,14 ºC**

### 2️⃣ Desvios ao quadrado:
| Dia | Temperatura | (xᵢ − x̄)²           |
|-----|-------------|----------------------|
| 1   | 22          | (−0,14)² = 0,02      |
| 2   | 23          | (0,86)² = 0,74       |
| 3   | 22          | (−0,14)² = 0,02      |
| 4   | 21          | (−1,14)² = 1,30      |
| 5   | 22          | (−0,14)² = 0,02      |
| 6   | 23          | (0,86)² = 0,74       |
| 7   | 22          | (−0,14)² = 0,02      |

### 3️⃣ Soma dos desvios²:
> 0,02 + 0,74 + 0,02 + 1,30 + 0,02 + 0,74 + 0,02 = **2,86**

### 4️⃣ Variância (amostral):
> s² = 2,86 ÷ (7 − 1) = 2,86 ÷ 6 = **0,48**

> Por que dividir por (n − 1)? — **Correção de Bessel**
> Quando calculamos a variância de uma **amostra** (e não da população inteira), usamos **n − 1** em vez de **n** para tornar a estimativa mais precisa. Essa correção é chamada de **ajuste de Bessel**.

### 5️⃣ Desvio padrão:
> s = √0,48 ≈ **0,69 ºC**

---

## 📌 Interpretação

| Desvio Padrão | Interpretação                     |
|----------------|----------------------------------|
| 0 a 1,5 ºC      | 🔹 Clima estável (baixa variação) |
| 1,5 a 4 ºC      | ⚠️ Variação moderada              |
| Acima de 4 ºC   | 🔥 Clima instável                |

---

✏️ **Resumo:**  
- A **população** usa **N (30)** no denominador.  
- A **amostra** usa **n − 1 (6)** para corrigir o viés da estimativa.  
- O **desvio padrão** mede o quanto os dados variam em torno da média.

---

🔗 Fonte: https://brasilescola.uol.com.br/matematica/desvio-padrao.htm
