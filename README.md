# eduardobrunetto.github.io
Predição do preço de corridas de Uber e Lyft
               Regressão 
               
               
               Contexto:
Esse dataset foi coletado fazendo consultas de preço para corrida de aplicativo entre
algumas regiões de Boston durante novembro e dezembro de 2018. Ele possui quase 700 mil
instâncias contendo como atributos o preço da corrida, se é Uber ou Lyft, categoria (black, X, ..),
horário, entre outras categorias, totalizando 10 variáveis entre categóricas e numéricas. Além
disso, foram coletadas separadamente informações ambientais a respeito desses períodos, se
estava chovendo, previsão do tempo, temperatura entre outros. Todas essas variáveis foram
compiladas e totalizam 57 entre categóricas e numéricas. A coleta inicial das variáveis e criação
do dataset foi realizada pelo usuário RaviMunde e é explicada neste link do Kaggle: 
https://www.kaggle.com/datasets/ravi72munde/uber-lyft-cab-prices?sort=votes&select=cab_rides.csv. 
Já a compilação dos dados numéricos e adição de outras variáveis foram feitas pelo usuário BM neste
link do Kaggle: https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma?datasetId=370703&sortBy=voteCount&sort=votes

Foi um trabalho realizado na disciplina Tópicos Avançados em Controle processos de sinais IV (Machine Learning)
e a ideia é se familiarizar com o processo de criação e utilização de modelos de machine learning, assim como seus pontos fortes e dificuldades.
Nesse contexto, iremos trabalhar com uma boa parte dessa pipeline de trabalho. Primeiramente,
conseguir os dados a serem utilizados neste estudo, nesse caso os dados já foram coletados e
serão baixados e analisados. Na sequência, fazer análises iniciais sobre eles, separá-los em
treinamento, validação e teste, estudar ainda melhor as variáveis e sua correlação inicial com a
saída. Por fim, treinar e testar diversos modelos e observar seus resultados para diferentes casos
desejados de aplicação.

OBJETIVO: prever o valor esperado de uma corrida com base nos outros dados
disponíveis, tendo como métrica a ser otimizada o MAPE (Mean Absolute Percentage Error).
