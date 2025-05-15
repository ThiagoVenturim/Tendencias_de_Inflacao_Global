# **Dicionário de Dados — Global Inflation Data**
Este conjunto de dados contém informações sobre a taxa média anual de inflação (índice de preços ao consumidor) para diversos países ao longo dos anos de 1980 a 2024.



| Nome da Coluna     | Tipo de Dado         | Descrição                                                                 | Classificação               |
|--------------------|----------------------|---------------------------------------------------------------------------|-----------------------------|
| `country_name`     | string               | Nome do país.                                                             | Categórica nominal          |
| `indicator_name`   | string               | Nome do indicador econômico. Nesse caso, sempre "Annual average inflation (consumer prices) rate". | Categórica nominal          |
| `1980` a `2024`    | float (numérico)     | Taxa média anual de inflação para o respectivo ano (em %).               | Quantitativa contínua       |


---

*Obs:*

- As colunas de 1980 a 2024 representam valores contínuos (percentuais de inflação).
- Não há variáveis binárias ou ordinais originais na base.
- Pode-se derivar variáveis categóricas ou ordinais a partir da inflação (ex: "baixa", "moderada", "alta").
- Após a limpeza selecionamos somente as colunas 2015 a 2024.
