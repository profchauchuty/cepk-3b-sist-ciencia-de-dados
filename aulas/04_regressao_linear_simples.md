### 📊 **Conceitos Básicos de Regressão Linear Simples**

| Conceito                     | Definição                                                                 | Exemplo                                                                 |
|-------------------------------|---------------------------------------------------------------------------|-------------------------------------------------------------------------|
| **Variável Dependente (Y)**   | Valor que queremos **prever ou explicar**.                                | Nota obtida em uma prova.                                               |
| **Variável Independente (X)** | Valor usado para **explicar ou prever** a variável dependente.           | Tempo de estudo em horas.                                               |
| **Modelo de Regressão Linear**| Relação **linear** entre X e Y, representada por uma equação: Y = a + bX | Prever a nota de um aluno com base no tempo de estudo: Y = 2 + 1X      |
| **Coeficiente Angular (b)**   | Indica **quanto Y muda quando X aumenta 1 unidade**.                     | b = 1 → cada hora de estudo aumenta a nota em 1 ponto.                  |
| **Coeficiente Linear (a)**    | Valor de Y quando X = 0 (ponto de interseção com o eixo Y).              | a = 2 → sem estudar, a nota estimada seria 2 pontos.                   |
| **Resíduos (erro)**           | Diferença entre o valor observado e o valor previsto pelo modelo.        | Nota real 4, prevista 4 → resíduo = 0                                     |
| **R² (coeficiente de determinação)** | Indica **quanto da variação de Y é explicada por X**.            | R² = 1 → 100% da variação das notas é explicada pelo tempo de estudo.  |
| **Previsão**                  | Valor estimado de Y para um dado X usando a equação da regressão.        | Prever a nota de um aluno que estudou 5 horas: Y = a + bX               |
| **Tendência**                 | Direção geral da relação entre X e Y (positiva ou negativa).             | Positiva: quanto mais tempo de estudo, maior a nota.                    |

---

## 📝 Exemplo - Nota x Tempo de Estudo (5 alunos)

### Fórmula - Regressão Linear Simples:

> Y = a + bX  

> b = Σ((Xᵢ − X̄)(Yᵢ − Ȳ)) ÷ Σ((Xᵢ − X̄)²)  
> a = Ȳ − bX̄

### Dados:
| Aluno | Tempo de Estudo (X) | Nota (Y) |
|-------|--------------------|----------|
| 1     | 0                  | 2        |
| 2     | 2                  | 4        |
| 3     | 4                  | 6        |
| 4     | 6                  | 8        |
| 5     | 8                  | 10       |

### 1️⃣ Médias:
> X̄ = (0+2+4+6+8)/5 = 4  
> Ȳ = (2+4+6+8+10)/5 = 6

### 2️⃣ Coeficiente Angular (b):
| Xᵢ | Yᵢ | Xᵢ−X̄ | Yᵢ−Ȳ | (Xᵢ−X̄)(Yᵢ−Ȳ) | (Xᵢ−X̄)² |
|----|----|--------|-------|----------------|-----------|
| 0  | 2  | -4     | -4    | 16             | 16        |
| 2  | 4  | -2     | -2    | 4              | 4         |
| 4  | 6  | 0      | 0     | 0              | 0         |
| 6  | 8  | 2      | 2     | 4              | 4         |
| 8  |10  | 4      | 4     | 16             | 16        |

> Σ((Xᵢ−X̄)(Yᵢ−Ȳ)) = 40  
> Σ((Xᵢ−X̄)²) = 40  

> b = 40 / 40 = 1

### 3️⃣ Coeficiente Linear (a):
> a = Ȳ − bX̄ = 6 − 1×4 = 2

### 4️⃣ Equação da Regressão:
> Y = 2 + 1·X

### 5️⃣ Previsão:
> Nota de um aluno que estudou 5 horas (X = 5):  
> Y = 2 + 1×5 = 7 pontos

---

## 📌 Interpretação

| Coeficiente | Interpretação                                      |
|-------------|----------------------------------------------------|
| b = 1       | Cada hora de estudo aumenta a nota em 1 ponto.     |
| a = 2       | Sem estudar, nota estimada é 2 pontos.            |
| R² = 1      | 100% da variação das notas é explicada pelo tempo de estudo. |

---

✏️ **Resumo:**  
- A **regressão linear simples** estima a relação entre **tempo de estudo (X)** e **nota (Y)**.  
- O **coeficiente angular (b)** indica quanto a nota aumenta a cada hora de estudo.  
- O **coeficiente linear (a)** indica a nota estimada sem estudo.  
- Os **resíduos** mostram a diferença entre nota real e prevista.  

---

🔗 Fonte: https://brasilescola.uol.com.br/matematica/regressao-linear.htm
