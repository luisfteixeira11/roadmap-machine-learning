# Tópicos de Deep Learning
Aprofundando no Aprendizado de Máquina, é essencial estudar Redes Neurais Profundas para resolver problemas complexos com dados não estruturados, como imagens, áudios e textos. O Deep Learning é fundamental quando grandes volumes de dados precisam ser analisados com alta precisão.

## Redes Neurais

Redes Neurais são modelos computacionais inspirados no cérebro humano, compostos por camadas de unidades chamadas neurônios artificiais. Cada neurônio recebe entradas, aplica uma função de ativação e transmite um sinal adiante, permitindo que o modelo aprenda padrões e relações complexas.

Principais conceitos:

- Perceptron e neurônio artificial: unidade básica que combina entradas e pesos para gerar uma saída.
- Camadas: entrada, escondida e saída; arquiteturas com várias camadas são chamadas de redes profundas.
- Funções de ativação: ReLU, sigmoid, tanh, softmax.
- Treinamento: feedforward, cálculo de erro e backpropagation para ajustar pesos.

Aplicações comuns:

- Reconhecimento de fala e imagens: detecção de voz, reconhecimento facial e classificação de objetos.
- Medicina: análise de exames de imagem, diagnóstico assistido e triagem de doenças.
- Logística: previsão de demanda, otimização de rotas e gerenciamento de estoques.

Recursos úteis:

- [Site USP de Redes Neurais e MLP](https://sites.icmc.usp.br/andre/research/neural/)
- [Artigo do Medium com uma Introdução a redes neurais com Keras](https://medium.com/analytics-vidhya/simplest-introduction-to-neural-networks-in-keras-c6ce8d666461)

## Aprendizado Profundo (Deep Learning)

Deep Learning é um subconjunto de Machine Learning que utiliza redes neurais com muitas camadas para extrair características automaticamente. Enquanto o Machine Learning tradicional depende de engenharia de features, o Deep Learning aprende representações diretamente dos dados.

Tabela comparativa: Machine Learning x Deep Learning

| Característica | Machine Learning | Deep Learning |
|----|----|----|
| Dados | Funciona melhor com conjuntos menores de dados | Requer grandes volumes de dados |
| Feature Engineering | Manual | Automatizada |
| Tempo de Treinamento | Curto a moderado | Longo, dependendo da arquitetura |
| Hardware | CPUs são suficientes para muitos casos | GPUs/TPUs aceleram treino e inferência |
| Estrutura | Algoritmos estatísticos e de otimização | Redes neurais profundas e arquiteturas especializadas |
| Exemplos de frameworks | [Scikit-learn](https://scikit-learn.org/stable/index.html), [XGBoost](https://xgboost.ai/) | [PyTorch](https://pytorch.org/), [TensorFlow](https://www.tensorflow.org/?hl=pt-br), [Keras](https://keras.io/) |

Vantagens do Deep Learning:

- Capacidade de aprender a partir de dados brutos.
- Excelente desempenho em imagens, áudio e texto.
- Flexibilidade para criar arquiteturas complexas como CNNs, RNNs e Transformers.

Limitações e desafios:

- Alto custo computacional.
- Necessidade de grande volume de dados rotulados.
- Risco de overfitting e explicabilidade reduzida.

Recursos úteis:

- [Página da IBM sobre o Aprendizado Profundo](https://www.ibm.com/br-pt/think/topics/deep-learning)
- [Artigo do Medium sobre MLPs](https://medium.com/@nlunge786/a-deep-architecture-multi-layer-perceptron-164bc5ff3842)

## Aprendizado Federado

Aprendizado Federado é uma técnica de treinamento distribuído que mantém os dados localmente em dispositivos ou servidores. Em vez de centralizar os dados, o modelo é enviado para cada local, atualizado localmente e depois agregado, preservando privacidade e segurança.

Aplicações:

- Educação: treinamentos colaborativos entre universidades e instituições sem compartilhar dados sensíveis.
- Previsão de texto: teclados como o Gboard atualizam modelos sem enviar o texto do usuário para servidores centrais.
- IoT: dispositivos conectados cooperam para melhorar modelos locais sem transferir grandes volumes de dados.

Vantagens:

- Proteção de dados pessoais.
- Redução de custo de transferência de dados.
- Conformidade com regulamentos de privacidade.

Recursos úteis:

- [Página Google Cloud sobre Aprendizado Federado](https://cloud.google.com/discover/what-is-federated-learning?hl=pt-BR)
- [Vídeo do canal Sandeco que aborda o Aprendizado Federado](https://www.youtube.com/watch?v=3xZdBTE6IXg)
- [Página Zup sobre Aprendizado Federado](https://zup.com.br/blog/federated-learning/)
- [Site da Google AI sobre Aprendizado Federado](https://federated.withgoogle.com)
- [Site da documentação do framework flower](https://flower.ai/docs)
- [Playlist de tutorial de Simulação de IA federada com Flower](https://www.youtube.com/watch?v=XK_dRVcSZqg&list=PLNG4feLHqCWkdlSrEL2xbCtGa6QBxlUZb&index=1)

## Visão Computacional

Visão Computacional é a área que permite que máquinas entendam imagens e vídeos. No Deep Learning, isso é feito principalmente com redes neurais convolucionais (CNNs), que identificam bordas, texturas e objetos em diferentes níveis de abstração.

Principais tarefas:

- Classificação de imagens: identificar a categoria de uma imagem.
- Detecção de objetos: localizar e classificar múltiplos objetos em uma imagem.
- Segmentação semântica: rotular cada pixel de uma imagem.
- Reconhecimento facial, análise de vídeo e visão robótica.

Arquiteturas comuns:

- CNNs: VGG, ResNet, Inception.
- Detectores: YOLO, SSD, Faster R-CNN.
- Segmentação: U-Net, Mask R-CNN.

## Deep Reinforcement Learning

Deep Reinforcement Learning combina aprendizado por reforço com redes neurais profundas para aprender políticas em ambientes dinâmicos. O agente aprende ações que maximizam recompensas ao interagir com o ambiente.

Componentes principais:

- Agente, ambiente, estado, ação e recompensa.
- Exploração vs. exploração.
- Função de valor e política.

Técnicas e algoritmos:

- Q-Learning profundo (DQN).
- Policy Gradient e Actor-Critic.
- PPO, A3C e DDPG.

Aplicações típicas:

- Jogos: aprendizado de estratégia em jogos como Go, xadrez e jogos eletrônicos.
- Robótica: controle de movimentos e navegação autônoma.
- Sistemas de recomendação dinâmicos.

## Processamento de Linguagem Natural (PLN)

PLN usa Deep Learning para entender e gerar texto. Redes recorrentes e transformers permitem capturar contexto e significado em sequências de palavras.

Principais técnicas:

- RNNs, LSTMs e GRUs para dados sequenciais.
- Transformers e atenção para modelar dependências de longo alcance.
- Representações de linguagem: embeddings, word2vec, BERT e GPT.

Aplicações:

- Tradução automática.
- Análise de sentimento.
- Resposta automática e chatbots.
- Extração de informações e sumarização de texto.

## Modelos Generativos

Modelos generativos criam novos dados a partir de exemplos existentes. No Deep Learning, eles são usados para gerar imagens, texto, áudio e outras modalidades.

Principais abordagens:

- GANs (Generative Adversarial Networks): dois modelos competem para gerar dados realistas.
- VAEs (Variational Autoencoders): aprendem uma representação latente contínua.
- Modelos de difusão: produzem amostras passo a passo a partir de ruído.
- Modelos de linguagem generativa: GPT, BERT e outros transformers que geram texto.

Aplicações práticas:

- Geração de imagens e arte.
- Síntese de voz e áudio.
- Criação de texto, tradução e conversas automatizadas.
- Design assistido, simulação e aumento de dados.
