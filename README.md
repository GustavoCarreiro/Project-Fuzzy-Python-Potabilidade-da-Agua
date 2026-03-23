## 💧 Sistema Fuzzy para Análise de Potabilidade da Água.

## 📌 Sobre o Projeto:
Este projeto foi desenvolvido como parte da disciplina de Inteligência Artificial (Projeto A3) e tem como objetivo aplicar Lógica Fuzzy para determinar a potabilidade da água com base em variáveis físico-químicas.

A solução classifica a água em três categorias:

- 🚫 Não potável
- ⚠️ Semi potável
- ✅ Potável

O sistema utiliza conceitos clássicos de sistemas fuzzy:
- Fuzzificação
- Inferência Fuzzy
- Defuzzificação

## 🧠 Tecnologias Utilizadas:
- Python
- Pandas
- NumPy
- Scikit-Fuzzy
  
## 📊 Dataset.
O projeto utiliza o dataset de potabilidade da água disponível no Kaggle:
🔗 https://www.kaggle.com/datasets/adityakadiwal/water-potability


## ⚙️ Funcionamento do Sistema:

**1. Fuzzificação**

Transforma valores numéricos em variáveis linguísticas.

**Variáveis de Entrada:**

- **pH** → ácido, neutro, alcalino
- **Cloramina** → baixa, média, alta
- **Turbidez** → transparente, turvo, muito turvo
- **Sólidos** → (considerado no modelo)

**Variável de Saída:**
- **Potabilidade** → não potável, semi potável, potável
  
**2. Inferência Fuzzy**

Define regras do tipo:

"Se pH é ácido e turbidez é alta, então água é não potável"

As regras são aplicadas simultaneamente para gerar uma saída fuzzy.

**3. Defuzzificação**

Converte o resultado fuzzy em um valor numérico que representa o nível de potabilidade.

3. Defuzzificação

Converte o resultado fuzzy em um valor numérico que representa o nível de potabilidade.
