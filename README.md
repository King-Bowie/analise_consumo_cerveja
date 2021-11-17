# estudo-consumo-cerveja

Estudo com análise descritiva e regressão linear com um dataset do kaggle sobre consumo de cerveja em uma cidade universitária de São Paulo, e na conclusão do projeto é realizado um simulador de vendas de litros cerveja com base nas variáveis chuva, temperatura máxima e final de semana


Bibliotecas usadas: Scikit learn, Pandas, Seaborn.

É utilizado o Pickle para transformar o modelo em um arquivo para ser facilmente usado em outros dispositivos sem a necessidade de todo o notebook e o processamento computacional.

Primeiro foi necessário analisar o dataset e descobrir qual eram as colunas e suas correlações com a coluna que queriamos prever que é consumo de cerveja.

É analisado também os outliers e percebemos que estes aumentos distintos são referentes a momento extremamente específicos como o início das aulas e o dia dos professores. 

Foi introduzido o conteúdo de machine learning, no qual, foi realizado treinamento com 30% dos dados e tivemos 73% de precisão. e um dado interessante que obtivemos desconsiderando as variáveis explicativas (chuva,final de semana e temperatura máxima) é a venda de cerveja 5951.97 litros.

Também tentamos fazer um outro modelo alterando uma variável explicativa, no qual é, temperatura máxima para temperatura média e tivemos uma previsão com menor precisão de 66% .
