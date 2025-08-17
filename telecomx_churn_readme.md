# 📡 Telecom X - Parte 2: Prevendo Cancelamento de Clientes

Bem-vindo(a) ao repositório do desafio **Telecom X - Parte 2**! 🚀

Este projeto faz parte de um estudo de **Data Science e Machine Learning** com foco em **redução de churn** (evasão de clientes). Aqui, foi construído um pipeline preditivo capaz de identificar quais clientes possuem maior chance de cancelar seus serviços.

---

## 🎯 Missão

- Desenvolver **modelos preditivos** para prever o cancelamento de clientes.
- Ajudar a empresa a **antecipar a evasão** e tomar decisões estratégicas.

## 🧠 Objetivos do Desafio

- Preparar e tratar os dados para modelagem (remoção de colunas, encoding, normalização).
- Realizar **análise de correlação** e seleção de variáveis.
- Treinar pelo menos dois modelos de classificação.
- Avaliar o desempenho com métricas de classificação.
- Interpretar resultados e gerar insights de negócio.

## 🛠️ Tecnologias e Ferramentas Utilizadas

- **Linguagem**: Python 🐍
- **Bibliotecas**: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Modelos Testados**:
  - Regressão Logística
  - Random Forest
  - KNN (K-Nearest Neighbors)
  - Árvore de Decisão

---

## 🔧 Preparação dos Dados

- **Remoção de colunas irrelevantes**: IDs e variáveis redundantes foram eliminadas.
- **Encoding**: variáveis categóricas foram transformadas em numéricas.
- **Normalização**: aplicada em modelos sensíveis à escala (como KNN e Regressão Logística).

---

## 🤖 Modelagem

Foram criados **4 modelos preditivos**:

1. **Regressão Logística** ✅

   - Melhor desempenho geral.
   - Fácil de interpretar.
   - Útil para identificar variáveis mais relevantes.

2. **Random Forest** 🌲

   - Robusto contra overfitting.
   - Captura relações complexas.
   - Bom desempenho, mas menor recall.

3. **KNN (K-Nearest Neighbors)** 👥

   - Simples e intuitivo.
   - Requer normalização.
   - Sofreu com dados desbalanceados.

4. **Árvore de Decisão** 🌳

   - Fácil de interpretar.
   - Suscetível a overfitting.
   - Pior desempenho geral.

---

## 📊 Avaliação dos Modelos

As métricas utilizadas foram:

- **Acurácia**
- **Precisão**
- **Recall**
- **F1-Score**
- **Matriz de Confusão**

📌 **Resultado Geral**:

- 🥇 **Regressão Logística** → melhor equilíbrio entre precisão e recall.
- 🥈 **Random Forest** → desempenho sólido, mas recall menor.
- 🥉 **KNN** → razoável, mas sofreu com desbalanceamento.
- 🚫 **Árvore de Decisão** → desempenho mais fraco.

---

## 📝 Conclusões

- O **modelo mais indicado** foi a **Regressão Logística**, por apresentar o melhor equilíbrio entre as métricas.
- Variáveis relacionadas a **tempo de contrato, tipo de serviço e forma de pagamento** foram cruciais para prever o cancelamento.
- Estratégias de retenção devem priorizar clientes com **baixo tempo de permanência e contratos mensais**, pois apresentam maior risco de evasão.

---

## 💡 Insights Estratégicos

- Investir em **fidelização de clientes recém-chegados**.
- Criar benefícios para quem migra de **contratos mensais para anuais**.
- Monitorar clientes com **formas de pagamento mais flexíveis**, que tendem a cancelar com mais facilidade.

---

## 🚀 Como Reproduzir o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/telecomx-churn.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Abra o Jupyter Notebook:
   ```bash
   jupyter notebook Challenge_TelecomX_2_BR.ipynb
   ```

---

## 📌 Conclusão Final

Este desafio mostrou como **Machine Learning pode ser aplicado de forma prática para reduzir churn** e apoiar a tomada de decisão estratégica. Mais do que algoritmos, o valor está em **transformar dados em ação**, permitindo que a empresa retenha clientes e aumente sua receita.

---

✨ *Projeto desenvolvido como desafio prático de Data Science. Aprendizado garantido e muita diversão no processo!* 😃

