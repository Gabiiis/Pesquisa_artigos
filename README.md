Uma das coisas que mais gosto em fazer pesquisa é encontrar ferramentas que facilitam o trabalho e abrem novas possibilidades de análise.
Neste material apresento o OpenAlex e como utilizá-lo no R para consultar metadados científicos. 

# OpenAlex no R

Este projeto utiliza o pacote OpenAlex para consultar metadados científicos da API OpenAlex diretamente no R.

## Instalação

```r
install.packages("openalexR")
```

## Carregando o pacote

```r
library(openalexR)
```

## Exemplo

```r
works <- oa_fetch(
  entity = "works",
  search = "machine learning"
)

head(works)
```

## Documentação

https://docs.openalex.org
https://openalex.org
