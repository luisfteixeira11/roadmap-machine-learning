
# Dados para o Aprendizado de Máquina
Na área de Aprendizado de Máquina, o profissional deve saber que o output do modelo é o resultado dos dados que foram fornecidos em um input, como analisar, manipular, limpar e extrair a entrada e a saída é fundamental para qualquer pessoa da área.
## Tabela do Roadmap
| Tópico | Descrição | Livro | Playlist | Página web |
|--------|-----------|----------|------|--------|
| **Exploração de Dados** | Crucial para entendimento dos padrões de dados e features, sendo útil para entender se os dados estão prontos. | em breve |
| **Limpeza e Pré-processamento** | É onde a pessoa passa mais tempo em ML, já que a qualidade dos dados afeta diretamente o desempenho e a efetividade do modelo. | em breve |
| **Visualização de Dados** | Fundamental para a exploração dos resultados, em bibliotecas como Matplotlib, Seaborn e Plotly. | em breve | [Visualização e Exploração de Dados - Cibele Russo](https://youtube.com/playlist?list=PLt7qVSwRVn5YEIvaMb02IJVKCpauWV-s9&si=KB4orMQLub3k9Oxz) |  |
| **SQL e Banco de Dados** | Geralmente os dados residem em Bancos de Dados e Sistemas, e o SQL facilita a manipulação dos dados. | em breve |
| **Engenharia de Features** | Entendendo o processo de transformar dados brutos em variáveis, você consegue a capacidade de melhorar a performance e a precisão de um modelo. | em breve |
| **Web Scraping e APIs (extra)** | Muito útil para coletas de dados, mesmo não sendo imprescindível para um iniciante, é um ótimo tópico de estudo. | em breve |


## Bibliotecas de Python para lidar com dados

A seguir vou sugerir algumas bibliotecas da linguagem Pyhon para estudo para lidar com os dados para a área de ML.

**1. Manipulação de dados:**
- [Pandas](https://pandas.pydata.org/), a biblioteca fundamental para manipular os dados, utilizando DataFrames, facilitando a forma de lidar com tabelas, aquivos '.csv'...
- [Numpy](https://numpy.org/), a base de todas as bibliotecas de Python atualmente, essencial pra manipulação de arrays, matrizes e até operações matemáticas.
- [Polars](https://pola.rs/), uma versão alternativa ao Pandas, oferece DataFrames de alta performance, capaz de manipular dados muito rápidamente. [Um tutorial rápido do Chá con Tech.](https://www.youtube.com/watch?v=NEeo262jMao)

**2. Pré-Processamento de Dados:**
- [SciPy](https://scipy.org/pt/), uma biblioteca que extende o Numpy, tendo várias operações matemáticas/estatísticas para o pré-processamento e otimização de um modelo.
- [Feature-engine](https://feature-engine.trainindata.com/en/latest/), biblioteca focada especialmente na engenharia de features, destacando sua compatibilidade com o sklearn (o qual falaremos mais pra frente no roadmap).
 - [Scikit-learn](https://scikit-learn.org/stable/modules/preprocessing.html), uma das bibliotecas mais utilizadas na área de Machine Learning, possui muitos recursos de pré processamento além dos algoritmos de ML que virão a seguir no roadmap.

**3. Manipulação de dados para Big Data:**

- [Dask](https://www.dask.org/), para a manipulação de grandes conjuntos de dados (Big Data) que excedem a RAM, dividindo-os em menores, e buscando a melhor precisão do modelo de ML.

- [Vaex](https://vaex.readthedocs.io/en/latest/), biblioteca de alto desempenho para DataFrames, mais voltada para a visualização de conjuntos de dados massivos.

**4. Visualização de Dados:**

- [Matplotlib](https://matplotlib.org/), biblioteca base para gráficos 2D e 3D em Python.

- [Seaborn](https://seaborn.pydata.org/), beseada na matplotlib, busca criar gráficos atraentes com menos código.

- [Plotly](https://plotly.com/python/), biblioteca que permite a criação de gráficos desde mais simples até os mais profissionais.