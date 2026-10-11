# Dashboard de preços de combustíveis no RS (1º semestre de 2026)

Dashboard em Power BI feito a partir dos dados de preços de combustíveis da ANP, já limpos no Projeto 1 (https://github.com/Bruno678-BR/limpeza-dados-combustiveis-rs).

## Perguntas que o dashboard responde

1. Qual o preço médio de cada combustível no RS?
2. Como o preço mudou de janeiro a junho de 2026?
3. Quais municípios têm o preço médio mais alto (top 10)?

## O que tem na página

- Cartão com o preço médio geral e tabela com a média por produto.
- Gráfico de barras com o preço médio por produto.
- Gráfico de linhas com a evolução mensal, uma linha por produto.
- Ranking dos 10 municípios com maior preço médio, com os valores nas barras.
- Filtro por produto, que atualiza todos os visuais.

## Fonte dos dados

Série Histórica de Preços de Combustíveis e de GLP, ANP, 1º semestre de 2026.
https://dados.gov.br/dados/conjuntos-dados/serie-historica-de-precos-de-combustiveis-e-de-glp

O GNV ficou fora porque é vendido em R$/m³ e os demais em R$/litro.

## Observações

- No ranking de municípios o eixo começa em R$ 6,00 para destacar as diferenças, que na prática são de centavos. Por isso os valores aparecem nas barras.
- Sem filtro de produto, o ranking mistura todos os combustíveis. Para comparar municípios de forma justa, selecione um produto.
- Alguns municípios têm poucas coletas, então o ranking deve ser lido com cuidado.

## Arquivos

- `dashboard_combustiveis_rs.pbix`: arquivo do Power BI Desktop.
- PDF e imagem do dashboard.

## Ferramentas

Power BI Desktop, DAX (medida de preço médio).
