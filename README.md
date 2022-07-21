## Sobre o projeto Web Motors

** Foi realizada uma analise exploratoria dos dados que determinou alternativas para potencializar o recebimento de leads dos anúncios, onde foi elaborado 
um roteiro em duas partes para o desafio: 

** uma exploração dos dados que mostrou como a quantidade de leads varia de acordo
com as outras variáveis (por exemplo, a marca ou o modelo afetam o recebimento de
leads? O comportamento observado é o mesmo em todas as cidades?).

. Um modelo para determinar se um anúncio receberá lead.

. Outras informações, que eu tive acesso para ajudar a chegar a
conclusões melhores.

## Tarefas para a planilha de Vendas na Região de São Paulo

** Anuncio 

 - Cidade por Leads, quantidade de fotos, views, valor de anuncio, valor de mercado 
 - Prioridade por cliques de telefone e leads 
 - Média de vlr_anuncio e Média de vlr_mercado por prioridade 
 - Views por prioridade 
 - Leads por prioridade
 - Qtd_fotos por prioridade 
 - Vlr_anuncio por prioridade 
 - Vlr_mercado por prioridade
 
** Especificação 

 - Cambio por Valor de Anuncio e Mercado 
 - Combustível por Valor de Anuncio e Mercado
 - Combustível por views e leads 
 
** Indicador 

 - Total geral de leads 
 - quantidade de fotos 
 - Valor de Mercado 
 - Indicadores por leads, quantidade de fotos, views, anúncios 1
 - Indicadores por leads, quantidade de fotos, views, anúncios 2 
 
** Presença 

 - presença de freio abs por  total de propostas recebidas
 - presença de ar quente por total de propostas recebidas
 - presença de desembaçador traseiro por total de propostas recebidas 
 - presença de banco de couro por total de propostas recebidas
 - presença de sensor de chuva por total de propostas recebidas 
 - presença de sensor de estacionamento por total de propostas recebidas
 - presença de rodas de liga-leve por total de propostas recebidas 
 - presença de airbag por total de propostas recebidas 
 
** Ano_Veiculo 

- Meta de Máximo de Views em ano do modelo
- Meta Máximo de Leads por Ano 
- Meta Máximo de fotos por Ano
- Total de propostas recebidas por ano de modelo
- Ano Modelo por cliques de telefone, views, quantidades de telefone, valor de mercado e valor de anuncio 

## Passos para a tarefa 

    1 - Importando o caminho do disco para a Linguagem 
    2 - Lendo o caminho do disco 
    3 - Lendo as bibliotecas para a importação, manipulação e agrupamento dos dados no banco de dados
    4 - Divisão de Colunas dos dados da Web Motors, na intenção de criar entidade e relacionamento de tabelas para um banco de dados
    5 - Remoção de Dados Duplicados
    6 - Remoção de dados nulos
    7 - Leitura desses arquivos manipulados para um csv 
    8 - Criação do nome do banco de dados motors no software Postgry Sql no Windows 10 
    9 - Criação do Modelo Star Schema no Postrgy Sql chamado mkt_motors
    10 - Criação das tabelas indicador, fatos, presenca, especificação, veiculo, anuncio 
    11 - Importação dos arquivos csv, lidos no python para o Postgry Sql em suas respectivas tabelas 
    12 - Subindo por um servidor local do Power BI o banco de dados motors pela opção PostgrySql 
    13 -  Importação da base de dados motors no Power BI para o relacionamento de tabelas no Dax (Data Analitics Expression) 
    14 - Modelagem de dados Logícos Star Schema do Banco de dados 
    15 - Transformação dos dados no Power Query, para gerenciar com mais qualidade os tipos de dados desse banco para a geração dos gráficos 
    16 - Criação dos Paíneis Interativos na ferramenta do Power BI, com 5 paginas de relátorio 
   
## Tecnologias Utilizadas 

** O projeto foi desenvolvido com as seguintes tecnologia ** 

- [anaconda](https://www.anaconda.com/) 

- [jupyter notebook](https://jupyter.org/)

- [Python](https://www.python.org/)

- [PostgrySql](https://www.pgadmin.org/)

- [PowerBI](https://powerbi.microsoft.com/pt-br/)
 
 ** Pacotes para a manipulação e analise de dados
 
 - [pandas](https://harve.com.br/blog/programacao-python-blog/pandas-python-vantagens-e-como-comecar/) 
 
## ## Apresentação do Dashboards no Power BI - Web Motors 

** No Arquivo Web_motors.pbixx
   
