# Projeto Airbnb Melbourne - Análise de Dados
## Descrição do Projeto
Este projeto explora dados do Airbnb em Melbourne, Austrália, buscando identificar padrões e insights sobre o mercado de locações de curto prazo. O Airbnb, uma das maiores plataformas de hospedagem alternativa, conecta anfitriões com viajantes, oferecendo uma opção flexível e econômica em comparação aos hotéis tradicionais. Neste estudo, utilizamos dados disponibilizados pelo portal Inside Airbnb para explorar informações relevantes sobre as propriedades listadas em Melbourne, com foco em aspectos como localização, preços, tipos de quartos e avaliações.

## Objetivo
O objetivo deste projeto é realizar uma análise exploratória dos dados do Airbnb em Melbourne, respondendo a perguntas-chave, como:

*  Qual a média de preço dos imóveis por bairro?
* Quais são os tipos de quarto mais populares?
* Existe alguma correlação entre o número de avaliações e o preço?
* Quais bairros têm a maior disponibilidade de acomodações?
##Fonte dos Dados
Os dados utilizados para esta análise estão disponíveis publicamente no portal Inside Airbnb. O arquivo listings.csv fornece informações resumidas das listagens de imóveis, adequado para análises exploratórias e visualizações.

## Estrutura dos Dados
O conjunto de dados inclui as seguintes variáveis principais:

* id: Identificador do imóvel.
* name: Nome da propriedade.
* host_id e host_name: Identificador e nome do anfitrião.
* neighbourhood: Nome do bairro.
* latitude e longitude: Coordenadas da localização da propriedade.
* room_type: Tipo de quarto oferecido (inteiro, compartilhado, etc.).
* price: Preço de aluguel da propriedade.
* minimum_nights: Número mínimo de noites de hospedagem.
* number_of_reviews: Quantidade de avaliações.
* reviews_per_month: Média de avaliações por mês.
* availability_365: Número de dias que a propriedade está disponível em um ano.
* number_of_reviews_ltm: Avaliações nos últimos 12 meses.
## Primeiras Análises Realizadas
Para iniciar a análise, carregamos o dataset e verificamos suas características básicas:

Quantidade de Atributos e Entradas: O conjunto de dados possui um total de X entradas e Y atributos, cobrindo informações essenciais para a análise de mercado de hospedagens em Melbourne.
## Visualização dos Dados: 

Analisamos as primeiras linhas do dataset e identificamos os tipos de variáveis para compreender melhor a estrutura e integridade dos dados.
## Ferramentas Utilizadas
* Linguagem: Python
* Bibliotecas: Pandas, Matplotlib, Seaborn
## Próximos Passos
* Limpeza e tratamento de dados faltantes.
* Análise de correlações entre variáveis.
* Visualização e interpretação dos principais insights.


link no notebook no google colab : ' https://colab.research.google.com/drive/13R5qbE6UgymMpOeUmXB4wFrN0yrr5Jjy?usp=drive_open#scrollTo=agFkxHCSEKKe'
