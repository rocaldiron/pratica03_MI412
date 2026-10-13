# MI412 — Prática 3: comparação de K amostras independentes

Estudo por simulação, em R, de quatro procedimentos para comparar K grupos:
ANOVA de um fator, ANOVA de Welch, teste de Kruskal-Wallis e teste da Mediana
de Mood. O foco é o tamanho e o poder de cada teste quando normalidade,
homocedasticidade e balanceamento deixam de valer.

Feito em dupla com Nathan Cordeiro Ginak.

## Arquivos

- `MI412_Pratica03.qmd`: relatório em Quarto (código e interpretação).
- `MI412_Pratica03.pdf`: relatório renderizado.
- `dados_pratica03.csv`: vendas semanais (`SalesInThousands`) por loja, com tamanho do mercado, idade da loja e promoção.

## Como reproduzir

Instale `readr`, `dplyr`, `ggplot2`, `tidyr` e `knitr` e execute
`quarto render MI412_Pratica03.qmd`.
