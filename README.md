# projetoWalmart

1.	INTRODUÇÃO

Walmart é uma multinacional americana, sendo considerada a maior loja de varejo dos Estados Unidos, no ano de 2021 obteve um um lucro de $13.51 Bilhões. Fundada por Sam Walton em 1962, hoje opera com 10585 lojas em 24 países diferentes, visto isso nossos dados selecionam uma pequena amostra dessas lojas, as quais têm a demanda de uma expansão para que com isso seja feita uma escolha que melhor atende todos as características atribuídas de forma positiva e faça sentido essa expansão . 
Nesse contexto, para esse objetivo ser alcançado, ultilizamos da análise dos dados das lojas por meio da linguagem de programação Python, aplicando de filtros, estatísticas e visualização gráfica.

2.	ENTENDIMENTO DOS DADOS

Em análise, podemos estabelecer que iremos analisar no nosso Dataset os dados de 45 lojas Walmart, suas vendas semanais de 05/02/10 até 01/11/12 e algumas métricas econômicas e meteorológicas, subdivididas por dados com 6435 linhas de características e 8 colunas de atributos

3.	 COLETA E LIMPEZA DOS DADOS

Primeiramente, foi utilizado dos mecanismos do python, para se concluir a não presença de dados nulos ou duplicados. Posteriormente se identificou a demanda da troca dos dados do atributo “Date” do tipo object para datetime. Com essa modificação dos dados do atributo “Date” tivemos a possibilidade da criação da coluna “Week” que separa e conta a quantidade de semana precisamente passadas desde o primeiro dia do nosso dataset no dia 05/02/10 até o último no dia 01/11/12.

4.	EXPLORAÇÃO DOS DADOS

Analisando todas as lojas do nosso dataset podemos identificar algumas informações  importantes para a definição de qual loja será escolhida para a expansão. Primeiramente, as  médias de cada atributo da nossa tabela deve ser vista como algo primoroso, utilizando a função .describe() facilmente temos esses valores, assim temos como resultados aproximado:

Weekly Sales = 1046965
Temperature	= 60.66
Fuel Price = 3.36
CPI = 171.58
Unemployment = 8

À vista disso, os demais termos atribuídos ao nosso dataset apesar de conter informações que podem ser tidas como importantes, analisando friamente eles apresentam resultados quase iguais, onde a diferença é tão pequena que não pode ser vista como um fator a determinar qualquer escolha ou não apresentam informações que para a nossa análise não são realmente de  grande relevância, visto que é mais um complemento das informações importantes visualizadas anteriormente.
  
5.	ANÁLISE FINAL

Portanto a loja Walmart escolhida na nossa análise foi a loja 4 (Store 4). Destarte, ao observarmos a loja 4 vemos uma quantidade de vendas semanais muito acima da média em relação a todas as outras lojas, lembrando que a média é em torno de um pouco mais de 1000000 por semana, já na nossa loja escolhida temos um pouco mais de 2000000 por semana. Outro aspecto, o qual foi muito determinante no nosso estudo foi a taxa de desemprego que se encontra um pouco menor do que 6% nesse número é considerado muito positivo, visto que a média do nosso dataset é de aproximadamente 8%. Nesse contexto, ao olhar os Estados Unidos com um todo no período de 2010 a 2012 esses números também se mostram relevantes, já que a taxa variava de 10% a 8%. Informações um pouco menos relevantes na nossa análise, mas que podemos também citar é a temperatura e preço dos combustíveis. Em verdade, os valores dos dois são visto como positivos, a temperatura é um pouco acima da média geral mostrando dessa forma termos um lugar de clima quente, porém não de forma exagerada, já os preços dos combustíveis já é abaixo da média geral, dado que elevados preços nos combustíveis podem afetar a economia como um todo e esse preço abaixo do padrão ao meu ver é um fator relevante, porém não podemos da maior destaque a isso devido os preços dos combustíveis não terem uma grande discrepância. Por fim, um dado que pode colocar um ponto final da nossa escolha é o CPI (Consumer Price Index) ou IPC (Índice de Preços ao Consumidor) no Brasil, esse mede a variação de preços a partir da perspectiva do consumidor é uma maneira fundamental para medir as variações de tendências de compra e a inflação nos Estados Unidos. Desse modo, tendo um índice considerado muito bom do ponto de vista do dataset, eliminamos qualquer dúvida que a melhor escolha para a expansão é a loja 4 (Store 4).     
