== br-data-pipeline == 

Este projeto implementa uma pipeline de coleta e tratamento de dados públicos brasileiros.

Ele integra informações de duas fontes oficiais:

- IBGE: lista de municípios do Brasil.
- Banco Central (BCB): série histórica do IPCA (inflação).

== Funcionalidades == 

- Criação automática de pasta para dados brutos (raw).
- Consulta às APIs do IBGE e BCB.
- Conversão dos dados em DataFrame com pandas.
- Tratamento dos dados: ajuste de tipos, renomeação de colunas e remoção de nulos.
- Exportação dos resultados em CSV e Parquet.
