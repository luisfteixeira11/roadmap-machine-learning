
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
- [Vídeo IA Expert Academy DBSCAN](https://youtu.be/Lpd6HUtz580?si=JG7VFZ7-_kGW3Kgy)
- [Vídeo IA Expert Academy DBSCAN (prática)](https://youtu.be/VJGraVClYGA?si=q4Sp70tWPcLfR0dM)
- [Vídeo Universo Discreto sobre Clusterização Hieráquica](https://www.youtube.com/watch?v=I-NSH_-Vm4g&pp=ygUmYWxnb3JpdG1vIGNsdXN0ZXJpemHDp8OjbyBoaWVyw6FycXVpY2E%3D)
- #falta os de regra de associação e etc


## Aprendizado Autossupervisionado

O Aprendizado Autossupervisionado é um tipo de aprendizado que aprende de acordo com dados não rótulados, assim, buscando preencher os dados não rótulados com a geração de rótulos de acordo com os dados de entrada. Sendo como uma ponte entre o paradigma não supervisionado e o supervisionado para treinar grandes volumes de dados.

Possui aplicações em diversas áreas como:

- Processamento de Linguagem Natural(NLP): Previsão de palavras seguintes ou de lacunas em palavras (Ex.: Aprendizado -> Aprendizado Autossupervisionado, Apren -> Aprendizado);

- Visão Computacional: Processo de girar uma imagem para uma angulação correta;

- Processamento de Vídeo: Previsão de um próximo frame de um vídeo.

Seguem materiais que podem ser úteis:

-

## Aprendizado Semissupervisionado

O Aprendizado Semissupervisionado é um tipo de aprendizado que combina o aprendizado supervisionado com o aprendizado não supervisionado, utilizado em situaões onde tem alguns dados rotulados e muitos não rotulados, preenchendo a lacuna nos dados distanciando o aprendizado supervisionado e o não supervisionado, ideal para quando a rótulagem é dificultada por demora ou custo.

Possui aplicações em áreas como:

- Visão Computacional: Identificação do rosto de uma pessoa em diversas imagens;

- Medicina: Diagnóstico de imagens médicas que são pouco rótuladas;

- Setor Financeiro: Detecção de fraudes, onde poucas são confirmadas como fraude.

Seguem materiais que podem ser úteis:

-

## Aprendizado por Reforço

O Aprendizado por Reforço é um tipo de aprendizado de máquina onde o modelo aprende a tomar as melhores decisões baseado em tentativa e erro, buscando maximizar as "recompensas", no qual o agente executa uma ação, observa o resultado e recebe a recompensa.

Suas aplicações mais frequentes são:

- Jogos: Um agente pode jogar xadez, ou aprender a jogar com o próprio player;

- Robótica: Utilizado em carros autonomos, fazendo-os aprender na interação com o ambiente;

- Sistemas: Sistemas de recomendação, onde o sistema sempre está atento aos gostos atuais do usuário, como a Netflix para filmes.

Seguem materiais que podem ser úteis:

-


## Redes Neurais

As Redes Neurais são modelos computacionais que são feitos com a inspiração no Cérebro do Humano, onde camadas de nós interconectados (Neurônios artificiais), processam dados e reconhecem padrões, sendo essencial para tarefas complexas.

Suas aplicações são diversas:

- Reconhecimento de Fala e Imagens: Detecção de voz e reconhecimento facial;

- Medicina: Detecção de padrões em exames médicos;

- Logística: Otimização de rotas para transportes.

Seguem materiais que podem ser úteis:

-

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

-

## Aprendizado Federado

O Aprendizado Federado é uma técnica de aprendizado de máquina descentralizada, que permite o treinamento de modelos em múltiplos dispositivos/servidores sem precisar compartilhar os dados brutos. Esse tipo de Machine Learning não centraliza os dados, mas envia o modelo para onde os dados estão localizados, sendo eficiente em privacidade e segurança.

Possui aplicações em áreas como:

- Educação: Treinamento de modelos em Universidades com dados distribuídos em diferentes instituições, superando barreiras de privacidade ao não precisar centralizar esses dados;

- Previsão de Texto: O Google utiliza o Gboard para prever a próxima palavra sem ler a mensagem dos usuários;

- Internet das Coisas (IoT): Dispositivos que colaboram para otimizar operações locais.

Seguem materiais que podem ser úteis:

-

## Avaliação de um modelo de ML

A avaliação de um modelo de Machine learning mede o quão bem o modelo consegue generalizar para dados não vistos, com métricas específicas para cada tipo de modelo. Seu objetivo é visualizar a previsão e confiabilidade, alem de buscar previnir problemas como overfitting. Um exemplo de técnica avaliativa é o train/test split, já bem conhecido por muitos dividindo o teste em 80/20 para verificar o desempenho depois.

Seguem materiais que podem ser úteis:

-
