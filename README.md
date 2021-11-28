# Northeast and Southeast (Brazil) Municipal Elections

Exploratory analysis of Southeast and Northeast (both regions from Brazil) municipal elections from 2020 using geopandas and other visualization tools. The databases used on this analysis were taken from [Base dos Dados](https://basedosdados.org/) and from [geodata-br](https://github.com/tbrugz/geodata-br). Base dos Dados provided two databases, which were accessed throughout SQL queries: [Diretórios Brasileiros](https://basedosdados.org/dataset/br-bd-diretorios-brasil), from where were taken some metadata such as region, state acronyms and the id for each city; and [Eleições Brasileiras](https://basedosdados.org/dataset/br-tse-eleicoes), from where were taken the data about Brazilian elections. The GeoJSON file provided by geodata-br was loaded on the `create-database.py` file, on this project, and then imported into MySQL using some Python code. 
