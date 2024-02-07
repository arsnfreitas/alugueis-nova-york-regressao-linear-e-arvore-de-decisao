
# Projeto de Precificação de aluguéis em Nova York

O objetivo do projeto é analisar os dados fornecidos e criar um modelo preditivo que estime os preços dos alguéis com base nas informações disponíveis. Isso permitirá definir preços mais competitivos para melhorar o desempenho na área de revenda de automóveis usados.

## Descrição dos Datasets

### O projeto inclui:

**teste_precificacao**: Este dataset é composto por 48894 linhas e 16 colunas de informações (features). Cada linha representa um imóvel usado e a coluna "preco" é a variável a ser prevista.

id – Atua como uma chave exclusiva para cada anúncio nos dados do aplicativo

nome - Representa o nome do anúncio

host_id - Representa o id do usuário que hospedou o anúncio

host_name – Contém o nome do usuário que hospedou o anúncio

bairro_group - Contém o nome do bairro onde o anúncio está localizado

bairro - Contém o nome da área onde o anúncio está localizado

latitude - Contém a latitude do local

longitude - Contém a longitude do local

room_type – Contém o tipo de espaço de cada anúncio

price - Contém o preço por noite em dólares listado pelo anfitrião

minimo_noites - Contém o número mínimo de noites que o usuário deve reservar

numero_de_reviews - Contém o número de comentários dados a cada listagem

ultima_review - Contém a data da última revisão dada à listagem

reviews_por_mes - Contém o número de avaliações fornecidas por mês

calculado_host_listings_count - Contém a quantidade de listagem por host

disponibilidade_365 - Contém o número de dias em que o anúncio está disponível para reserva


## Configuração do Ambiente

Para reproduzir os resultados e executar o projeto, siga as instruções abaixo:

1. Clone este repositório para o seu ambiente local:

        git clone [https://github.com/guioliveiras/indicium-precificacao-veiculos.git](https://github.com/arsnfreitas/alugueis-nova-york-regressao-linear-e-arvore-de-decisao)

2. Certifique-se de ter as bibliotecas instaladas em seu ambiente Python:

        pip install -r requirements.txt

## Executando o Projeto

## Análise Estatística e EDA

## Previsão de Preços

Para realizar a previsão do preço a partir dos dados, foi utilizado um modelo de regressão linear e de árvore de decisão, sendo escolhido o último. Foram escolhidas variáveis relevantes e feitas transformações adequadas durante o pré-processamento para melhorar o desempenho do modelo. A métrica de performance escolhida para avaliar o modelo é o erro médio absoluto (MAE) e R2, que mede a diferença média entre as previsões e os preços reais.

## Resultado Final

O resultado final do modelo, contendo as previsões de preços para os dados de teste, está disponível no arquivo ***y_pred.csv*** e o modelo foi salvo como modelo.pkl.

## Agradecimentos

Agradeço a Indicium pela oportunidade de trabalhar neste projeto e a toda a equipe envolvida.
