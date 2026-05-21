
# Tópicos de Machine Learning
Para mergulhar de fato no Aprendizado de Máquina á necessário saber de que forma as máquinas aprendem e como que acontece por trás das principais bibliotecas de aprendizado de máquina. Por isso eu vou mudar um pouco a estrutura do roadmap nessa página com a finalidade de um destaque melhor para cada tópico.

## Aprendizado Supervisionado
O Aprendizado Supervisionado busca aprender com um conjunto de dados rótulados, ou seja, que contém as variáveis de entrada e as de "resposta" desejada pro conjunto de dados, buscando prever a variável Target, o que o modelo está buscando, com base nos inputs.

Esse tipo de aprendizado é dividido em:
 - Regressão: Previsão de valores contínuos. Ex.: Previsão de número de vendas de produtos;
 - Classificação: Previsão de rótulos categóricos(rótulos discretos); Ex.: Detecção de Spam...
 - Aprendizado Ensemble (Combinado/Híbrido): Abordagem de combinar múltiplos algoritmos/técnicas de aprendizado para resolver um problema complexo;
 - Aprendizado Profundo Supervisionado (iremos abordar esse tópico em [Deep Learning](#aprendizado-profundo-deep-learning)).

Seguem materiais que podem ser úteis:

 - [Página na Web com uma introdução ao ML](https://dataat.github.io/introducao-ao-machine-learning/index.html), contém o aprendizado supervisionado e o não supervisionado.
 - [Página da IBM sobre aprendizado supervisionado.](https://www.ibm.com/br-pt/think/topics/supervised-learning)
 - [Página Microsoft Azure sobre os algoritmos de aprendizado de máquina](https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-are-machine-learning-algorithms)
 - [Página sklearn aprendizado supervisionado](https://scikit-learn.org/stable/supervised_learning.html)
 - [Playlist Hashtag Programação com alguns Algoritmos Supervisionados (possui o K-means que é não Supervisionado)](https://youtube.com/playlist?list=PLpdAy0tYrnKw68i1Oo5oXairTtSmagbof&si=pvW5SVbgxnAWIu2Y)
 - [Vídeo Regressão Linear, Múltipla e Polinomial - Abel Siqueira](https://youtu.be/G6yGrsjMxls?si=69VyEgDxSowC8zbh)
 - [Vídeo Classificação - Eduardo | Ciência de Dados](https://youtu.be/_RAi7eTZYmA?si=iZdZS9_33tvPRuHi)
 - [Ensemble Learning - Emma Ding](https://youtu.be/sN5ZcJLDMaE?si=iujchPt4quBMCMoN)
 - [Página sklearn sobre Ensemble Learning](https://scikit-learn.org/stable/modules/ensemble.html)
 - [Curso Machine Learning Specialization - Andrew Ng (legendas português no canal Youtube deles)](https://www.deeplearning.ai/courses/machine-learning-specialization/)
 


## Aprendizado não Supervisionado

O Aprendizado não Supervisionado é um tipo de aprendizado de máquina que busca aprender com dados não rótulados, procurando padrões ocultos, agrupamentos sem intervenção humana. Há várias aplicações como em Exploração de Dados, detecção de anomalias e recomendações de conteúdo.

Suas principais técnicas são:
- Clustering: Organização de dados em grupos com base na semelhança; Ex.: Compressão de Imagem.
- Redução de Dimensionalidade(também existe na supervisionada, porém com objetivos diferentes): Técnica para facilitar o pré processamento, simplificando os dados para melhor visualização e reduzindo custos computacionais;
- Regras de Associação: Identificação de dependências e relações entre variáveis para otimização. Ex.: Análise de compras (se compra pão, também compra manteiga).

Seguem materiais que podem ser úteis:

- [Página da IBM sobre aprendizado não supervisionado.](https://www.ibm.com/br-pt/think/topics/unsupervised-learning#2014952965)
- [Vídeo Hashtag Programação sobre aprendizado não supervisionado e teórico sobre algoritmo K-means.](https://www.youtube.com/watch?v=q05qbU8FYKU&pp=ygUhYXByZW5kaXphZG8gZSBuw6NvIHN1cGVydmlzaW9uYWRv)
- [Vídeo Hashtag Programação de utilização do K-means.](https://www.youtube.com/watch?v=3mvtYH95LCw&pp=ygURYWxnb3JpdG1vIGsgbWVhbnPSBwkJrgoBhyohjO8%3D)
- [Vídeo IA Expert Academy DBSCAN.](https://youtu.be/Lpd6HUtz580?si=JG7VFZ7-_kGW3Kgy)
- [Vídeo IA Expert Academy DBSCAN (prática).](https://youtu.be/VJGraVClYGA?si=q4Sp70tWPcLfR0dM)
- [Vídeo Universo Discreto sobre Clusterização Hieráquica.](https://www.youtube.com/watch?v=I-NSH_-Vm4g&pp=ygUmYWxnb3JpdG1vIGNsdXN0ZXJpemHDp8OjbyBoaWVyw6FycXVpY2E%3D)
- [Vídeo Universo Discreto sobre Regras de Associação e Algoritmo Apriori.](https://youtu.be/YGEYty0xYc0?si=2ZfJY4--TUGcpVd8)
- [Vídeo Data Review sobre Redução de Dimensionalidade.](https://youtu.be/x68CrD6AZhY?si=imXg1DOSNXKV1hO7)
- [Artigo do Medium sobre Regra de Associação.](https://daniel-s-amador.medium.com/regras-de-associa%C3%A7%C3%A3o-b02bb9ce6ea3)
- [Página IBM sobre Detecção de Anomalias.](https://www.ibm.com/br-pt/think/topics/machine-learning-for-anomaly-detection)



## Aprendizado Semissupervisionado

O Aprendizado Semissupervisionado é um tipo de aprendizado que combina o aprendizado supervisionado com o aprendizado não supervisionado, utilizado em situaões onde tem alguns dados rotulados e muitos não rotulados, preenchendo a lacuna nos dados distanciando o aprendizado supervisionado e o não supervisionado, ideal para quando a rótulagem é dificultada por demora ou custo.

Possui aplicações em áreas como:

- Visão Computacional: Identificação do rosto de uma pessoa em diversas imagens;

- Medicina: Diagnóstico de imagens médicas que são pouco rótuladas;

- Setor Financeiro: Detecção de fraudes, onde poucas são confirmadas como fraude.

Seguem materiais que podem ser úteis:

- [Página IBM sobre Aprendizado Semissupervisionado.](https://www.ibm.com/br-pt/think/topics/semi-supervised-learning)
- [Página Oracle sobre Aprendizado Semissupervisionado.](https://www.oracle.com/br/artificial-intelligence/machine-learning/semi-supervised-learning/)
- [Artigo Medium com uma introdução geral sobre o tipo de aprendizado semissupervisionado.](https://medium.com/datalab-log/uma-introdu%C3%A7%C3%A3o-ao-aprendizado-semissupervisionado-ssl-9f2354314796)



## Aprendizado por Reforço

O Aprendizado por Reforço é um tipo de aprendizado de máquina onde o modelo aprende a tomar as melhores decisões baseado em tentativa e erro, buscando maximizar as "recompensas", no qual o agente executa uma ação, observa o resultado e recebe a recompensa.

Suas aplicações mais frequentes são:

- Jogos: Um agente pode jogar xadez, ou aprender a jogar com o próprio player;

- Robótica: Utilizado em carros autonomos, fazendo-os aprender na interação com o ambiente;

- Sistemas: Sistemas de recomendação, onde o sistema sempre está atento aos gostos atuais do usuário, como a Netflix para filmes.

Seguem materiais que podem ser úteis:

- [Artigo no Medium sobre o Aprendizado por Reforço](https://medium.com/datarisk-io/conceitos-para-enteder-reinforcement-learning-2b04d68bf4f9)
- [Artigo do Medium de Aprendizado por Reforço (possui uma série de artigos sobre)](https://medium.com/turing-talks/aprendizado-por-refor%C3%A7o-1-introdu%C3%A7%C3%A3o-7382ebb641ab)
- [Repositório Turing USP com um guia sobre Aprendizado por Reforço](https://github.com/turing-usp/Aprendizado-por-Reforco)



## Redes Neurais

As Redes Neurais são modelos computacionais que são feitos com a inspiração no Cérebro do Humano, onde camadas de nós interconectados (Neurônios artificiais), processam dados e reconhecem padrões, sendo essencial para tarefas complexas.

Suas aplicações são diversas:

- Reconhecimento de Fala e Imagens: Detecção de voz e reconhecimento facial;

- Medicina: Detecção de padrões em exames médicos;

- Logística: Otimização de rotas para transportes.

Seguem materiais que podem ser úteis:

- [Site USP de Redes Neurais e MLP](https://sites.icmc.usp.br/andre/research/neural/)
- [Artigo do Medium com uma Introdução a redes neurais com Keras](https://medium.com/analytics-vidhya/simplest-introduction-to-neural-networks-in-keras-c6ce8d666461)



## Aprendizado Profundo (Deep Learning)

Subconjunto do Machine Learning, baseado na utilização de redes neurais artificiais com várias camadas, projetadas para simular o cérebro humano. Processando grandes volumes de dados não estruturados, o Deep Learning consegue identificar padrões complexos, prever, e automaticamente aprender sem precisar de muita engenharia de recursos.

Tabela Comparativa: Machine Learning x Deep Learning

| Característica | Machine Learning | Deep Learning |
|----|----|----|
| Dados | Funciona melhor com menor quantidade de dados  | Precisa de Grande volume de dados. |
| Feature Engineering | Manual | Automática |
| Tempo de Treinamento | Baixo (cerca de minutos, horas) | Longo (dias, até semanas) |
| Hardware | Geralmente CPU é mais utilizada | Utiliza-se GPUs para acelerar o treinamento, necessitando de alto poder computacional |
| Estrutura | Algoritmos baseados em estatística | Redes Neurais profundas |
| Frameworks | [Scikit-learn](https://scikit-learn.org/stable/index.html), [XGBoost](https://xgboost.ai/)... | [Pytorch](https://pytorch.org/), [TensorFlow](https://www.tensorflow.org/?hl=pt-br), [Keras](https://keras.io/)... |

Possui diversas aplicações em várias áreas como:

- Visão Computacional: Identificação de objetos, rosto e imagens;

- IA Generativa: Criação de imagens, textos e vídeos;

- Corporativo: Otimização de estoques.

Seguem materiais que podem ser úteis:

- [Página da IBM sobre o Aprendizado Profundo](https://www.ibm.com/br-pt/think/topics/deep-learning)



## Aprendizado Autossupervisionado

O Aprendizado Autossupervisionado é um tipo de aprendizado que aprende de acordo com dados não rótulados, assim, buscando preencher os dados não rótulados com a geração de rótulos de acordo com os dados de entrada. Sendo como uma ponte entre o paradigma não supervisionado e o supervisionado para treinar grandes volumes de dados.

Possui aplicações em diversas áreas como:

- Processamento de Linguagem Natural(NLP): Previsão de palavras seguintes ou de lacunas em palavras (Ex.: Aprendizado -> Aprendizado Autossupervisionado, Apren -> Aprendizado);

- Visão Computacional: Processo de girar uma imagem para uma angulação correta;

- Processamento de Vídeo: Previsão de um próximo frame de um vídeo.

Seguem materiais que podem ser úteis:

- [Página da IBM sobre o Aprendizado Autossupervisionado](https://www.ibm.com/br-pt/think/topics/self-supervised-learning)
- [Página Geek for Geeks sobre Aprendizado Autossupervisionado (Inglês)](https://www.geeksforgeeks.org/machine-learning/self-supervised-learning-ssl/)
- [Página Meta sobre Aprendizado Autossupervisionado (Inglês)](https://ai.meta.com/blog/self-supervised-learning-the-dark-matter-of-intelligence/)



## Aprendizado Federado

O Aprendizado Federado é uma técnica de aprendizado de máquina descentralizada, que permite o treinamento de modelos em múltiplos dispositivos/servidores sem precisar compartilhar os dados brutos. Esse tipo de Machine Learning não centraliza os dados, mas envia o modelo para onde os dados estão localizados, sendo eficiente em privacidade e segurança.

Possui aplicações em áreas como:

- Educação: Treinamento de modelos em Universidades com dados distribuídos em diferentes instituições, superando barreiras de privacidade ao não precisar centralizar esses dados;

- Previsão de Texto: O Google utiliza o Gboard para prever a próxima palavra sem ler a mensagem dos usuários;

- Internet das Coisas (IoT): Dispositivos que colaboram para otimizar operações locais.

Seguem materiais que podem ser úteis:

- [Página Google Cloud sobre Aprendizado Federado](https://cloud.google.com/discover/what-is-federated-learning?hl=pt-BR)

## Avaliação de um modelo de ML

A avaliação de um modelo de Machine learning mede o quão bem o modelo consegue generalizar para dados não vistos, com métricas específicas para cada tipo de modelo. Seu objetivo é visualizar a previsão e confiabilidade, alem de buscar previnir problemas como overfitting. Um exemplo de técnica avaliativa é o train/test split, já bem conhecido por muitos dividindo o teste em 80/20 para verificar o desempenho depois.

Seguem materiais que podem ser úteis:

- [Artigo Medium com as principais métricas de avaliação de modelos](https://medium.com/data-hackers/principais-m%C3%A9tricas-de-classifica%C3%A7%C3%A3o-de-modelos-em-machine-learning-94eeb4b40ea9)



# Bibliotecas Python para Machine Learning


- [Scikit-learn](https://scikit-learn.org/stable/#), bibilioteca mais popular de Machine Learning, possui os Algoritmos "Clássicos", abrange o Aprendizado Supervisionado e o não Supervisionado, até alguns algoritmos de redes neurais.

- [XGboost](https://xgboost.ai/), uma biblioteca de Gradient Boosting, sendo reconhecida por alta performance e eficiência computacional, bastante usada em competições de ciência de dados no [kaggle](https://www.kaggle.com/).

- [LightGBM](https://lightgbm.readthedocs.io/en/stable/#), outro framework de Gradient Boost de alto desempenho, desenvolvido pela Microsoft, otimiza Árvores de Regressão para Classificação, Regressão e Ranqueamento, também amplamente usada no kaggle.

- [CatBoost](https://catboost.ai/), desenvolvida pela Yandex, é mais uma biblioteca de Gradient Boost para Árvores de Decisão, mas com a vantagem de não precisar lidar com features categóricas.

- [TensorFlow](https://www.tensorflow.org/?hl=pt-br), plataforma open source desenvolvida pelo Google, utilizada pra Machine Learning e Deep Learning, se destaca pela sua aplicabilidade em uma ampla variedade de tarefas.

- [Pytorch](https://pytorch.org/), um framework de Machine Learning desenvolvido pela Meta, bastante usado para aplicações de Inteligência Artificial como Visão Computacional e PLN.

- [Keras] (https://keras.io/), é uma API de alto nível focada na facilidade da prototipação de Redes Neurais, sendo assim uma API de uso mais facilitado para criação de modelos, com a possibilidade de treinar modelos em outras bibliotecas como Pytorch e TensorFlow.

- [OpenCV](https://opencv.org/), é a maior biblioteca de Visão Computacional e processamento de imagens, oferecendo inúmeros algoritmos em sua documentação.

- [Stable Baselines](https://stable-baselines3.readthedocs.io/en/master/), biblioteca focada na implementação de Reinforcement Learning.

- [Natural Language Toolkit](https://www.nltk.org/), é uma das principais bibliotecas pra Processamento de Linguagem Natural.