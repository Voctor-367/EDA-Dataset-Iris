# Análise Exploratória de Dados (EDA) - Dataset Iris
*Um projeto de EDA profissional utilizando Pandas, Matplotlib e Seaborn para extrair insights do clássico dataset Iris.*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python: 3.9+](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/downloads/)

## 📖 Sobre o Projeto
Este repositório contém uma Análise Exploratória de Dados (EDA) realizada no famoso dataset **Iris**. O objetivo principal é aplicar técnicas de manipulação de dados, estatística descritiva e visualização para entender a estrutura, as distribuições e as relações entre as variáveis do conjunto de dados.

A análise parte de uma inspeção geral e aprofundando em detalhes de cada variável e suas correlações.

---

## 🎯 Objetivos da Análise
- **Inspeção Inicial:** Familiarizar-se com a estrutura do dataset (tipos de dados, dimensões, etc.).
- **Validação e Limpeza:** Verificar a qualidade dos dados, tratando valores nulos e duplicados.
- **Análise Univariada:** Entender a distribuição de cada característica individualmente.
- **Análise Bivariada:** Explorar a relação entre pares de variáveis para identificar padrões e correlações.
- **Geração de Insights:** Sumarizar as descobertas de forma clara e objetiva.

---

## 📊 O Dataset
O conjunto de dados Iris é um dos mais clássicos da literatura de Machine Learning. Ele contém 150 amostras de flores de íris, divididas igualmente em 3 espécies diferentes.

**Variáveis (Colunas):**
- `sepal_length`: Comprimento da sépala (em cm).
- `sepal_width`: Largura da sépala (em cm).
- `petal_length`: Comprimento da pétala (em cm).
- `petal_width`: Largura da pétala (em cm).
- `species`: A espécie da flor (variável alvo).

**Espécies (Classes):**
1.  `Setosa`
2.  `Versicolor`
3.  `Virginica`

---

## 🛠️ Ferramentas e Bibliotecas Utilizadas
O projeto foi desenvolvido inteiramente em Python, utilizando as seguintes bibliotecas:
- **Pandas:** Para manipulação e análise dos dados.
- **Matplotlib:** Para a criação de gráficos base.
- **Seaborn:** Para visualizações estatísticas mais elaboradas e esteticamente agradáveis.
- **Bokeh:** Utilizada para o carregamento inicial do dataset.
- **Jupyter Notebook / Google Colab:** Como ambiente de desenvolvimento interativo.

---

## 📈 Roadmap da Análise
A análise contida no notebook segue a seguinte estrutura:

1.  **Configuração do Ambiente:** Importação das bibliotecas e carregamento dos dados.
2.  **Inspeção Inicial:** Uso de `.head()`, `.info()`, `.shape` e `.describe()` para um primeiro contato com os dados.
3.  **Validação dos Dados:** Checagem de valores nulos e duplicados. Análise da distribuição das classes (balanceamento).
4.  **Análise Univariada e Bivariada:**
    -   Visualização da contagem de cada espécie com gráficos de barras.
    -   Análise da distribuição de cada característica numérica com boxplots.
    -   Cálculo de medidas de tendência central (média, mediana) e de dispersão (desvio padrão, variância) agrupadas por espécie.
5.  **Conclusões e Insights:** Sumarização dos principais achados da análise.

---

## 💡 Principais Insights e Conclusões

A análise revelou padrões claros que tornam este dataset ideal para tarefas de classificação:

-   ✅ **Qualidade dos Dados:** O dataset é de alta qualidade, sem valores nulos e com as classes perfeitamente balanceadas (50 amostras por espécie), garantindo uma base sólida para a análise.
-   🌸 **Distinção da Setosa:** A espécie *Setosa* é linearmente separável das outras duas. Suas medidas de pétala (`petal_length` e `petal_width`) são significativamente menores e possuem uma dispersão muito baixa, não se sobrepondo aos valores das outras espécies.
-   📈 **Correlação Positiva:** Existe uma forte correlação positiva entre o comprimento da pétala (`petal_length`), a largura da pétala (`petal_width`) e o comprimento da sépala (`sepal_length`). Isso indica que as características da pétala são os diferenciadores mais robustos entre as espécies.
-   🔬 **Sobreposição Parcial:** Embora as espécies *Versicolor* e *Virginica* apresentem alguma sobreposição, principalmente nas medidas da sépala, elas ainda são distinguíveis pela média e pela distribuição das medidas da pétala.
-   🎯 **Potencial para Modelagem:** A clara separabilidade dos grupos, especialmente da *Setosa*, sugere que algoritmos de classificação como Regressão Logística, SVM ou Árvores de Decisão teriam um alto potencial de sucesso e acurácia.

### Visualizações Chave

*Abaixo estão alguns dos gráficos gerados que ilustram os insights mencionados.*

**Distribuição das Espécies**
*O gráfico de barras mostra o perfeito balanceamento do dataset.*
![Contagem por Espécie](assets/countplot.png)

**Análise das Características por Espécie**
*Os boxplots mostram a distribuição de cada medida, evidenciando a separabilidade da espécie Setosa.*
![Boxplots por Característica](assets/boxplots.png)

---

## 👤 Autor
**[Seu Nome]**
- GitHub: [@Voctor-367](https://github.com/Voctor-367)
- LinkedIn: [Victor Fonteles](https://www.linkedin.com/in/victorfonteles)

---

## 📜 Licença
Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
