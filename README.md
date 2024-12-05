Você foi contratado pela empresa S&M Data Analytics para realizar a análise de um determinado
conjunto de dados de uma companhia de investimentos.
Nesse conjunto de dados há diversas informações sobre os ativos de investimentos Nome da ação,
preço da ação, qtde de cotas, valor de mercado da empresa
Sua tarefa consiste em realizar análise exploratória e implementar um algoritmo de aprendizado não
supervisionado que consiste em agrupar as ações com características semelhantes. Para essa tarefa são
necessários realizar as seguintes etapas do processo de descoberta do conhecimento:

1 - Preparação dos dados
Realize a importação de um conjunto de dados que contenha as seguintes colunas:
Nome ação: nome dação
Preço ação: Preço para compra da ação.
Qtde de cotas: Quantidade de cotas disponíveis da empresa.
Valor de mercado da empresa: Valor de mercado da empresa

2- Exploração dos dados
Explore os dados para entender a distribuição do preço da ação, qtde de cotas, valor de mercado
Plotar box plot do preço da ação para cada ativo para verificar outliers (Utilizar biblioteca seaborn)
a) Plotar box plot do valor de mercado da empresa para cada ativo para verificar outliers(Utilizar
biblioteca seaborn - sns.boxplot)
b) Utilizar df.info() para ver informações do conjunto de dados
c) Utilizar df.describe para ver informações do conjunto de dados

3 - Pré processamento dos dados
Realize qualquer pré-processamento necessário, como lidar com valores ausentes, codicar
variáveis categóricas, etc.
Utilizar o pdget_dummies(nome_dataframe,columns=[‘nome da coluna’],drop_rst=True) para
transformar a coluna de variáveis categóricas para True ou false para aplicar o algoritmo K-means
4 - Utilizar o algoritmo K-means com n_clusters = 4 para agrupar as ações com base nas
características :preço da ação, quantidade de cotas e valor de mercado,
a) Alterar o número de clusters para 5 e verificar o que acontece com os grupos formados
b) Alterar o número de clusters para 8 e verificar o que acontece com os grupos formados
c) Plotar o gráfico do cotovelo para n variando de 1 a 8 clusters
d) Plotar o gráfico da silhueta
5 - Plotar visualização dos clusters formados
a) Visualização 2d dos clusters formados
b) Visualização 3d dos clusters formados
5) Qual a maior vantagem do aprendizado não supervisionado diante o aprendizado supervisionado ?
