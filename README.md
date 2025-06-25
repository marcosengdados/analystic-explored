## 📦 Análise Exploratória de Dados Logísticos – Loggi

Este projeto tem como objetivo realizar uma análise exploratória de dados de entregas fornecidos pela Loggi, com foco em identificar padrões de distribuição, regiões com maior demanda e potenciais melhorias logísticas. A proposta foi desenvolvida como parte prática do curso de Analista de Dados da EBAC.

# 📌 Objetivos da Análise

Identificar regiões de origem e destino com maior volume de entregas.

Avaliar a distribuição de peso das entregas por região.

Visualizar pontos de entrega e hubs logísticos utilizando mapas e shapefiles.

Gerar insights para melhoria operacional e logística.

# 🔎 Etapas Desenvolvidas
Importação e exploração de dados JSON disponibilizados via GitHub.

Normalização e transformação dos dados usando pandas e json_normalize.

Geoprocessamento com geopandas, com destaque para:

Geocodificação reversa de coordenadas.

Integração de shapefiles do IBGE.

Visualização de dados com Seaborn e Matplotlib, incluindo:

Gráficos de distribuição por região e volume.

Boxplots por faixa de peso.

Mapas com entregas e hubs logísticos georreferenciados.

Identificação de padrões logísticos, como concentração de entregas e análise de regiões subatendidas.

# 🛠️ Tecnologias Utilizadas

Python	

**Linguagem principal da análise**

- Pandas	Manipulação e limpeza de dados
- GeoPandas	Geoprocessamento de dados espaciais
- Seaborn e Matplotlib	Criação de visualizações estatísticas
- Geopy	Geocodificação reversa
- JSON	Manipulação de dados estruturados
- Shapefiles IBGE	Base cartográfica do Distrito Federal

# 📍 Destaques Técnicos

Aplicação de explosão de dados aninhados (explode + json_normalize).

Enriquecimento de dados com geolocalização e mapas temáticos.

Análise de qualidade de dados e tratamento de valores nulos.

Visualização interativa da cobertura logística por região, com apoio de mapas shapefile.

# 📊 Resultados e Insights

A maior parte das entregas está concentrada em poucas regiões de destino.

A região df-0 apresenta subutilização, sugerindo revisão na estratégia de frota.

A maioria das entregas possui peso leve (até 1000 kg).

Necessidade de revisão de registros genéricos como “Brasília” para melhor segmentação.
Análise exploratória de dados logisticos, uma visão detalhada sobre o processo e melhorias
