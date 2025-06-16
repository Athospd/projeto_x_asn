# Relatorio Diario de Compliance
Athos Damiani
2025-06-16

Projeto de analise de dados para a area de compliance da Empresa X

Data e hora de atualizacao: 2025-06-16 18:36:58.296597

``` r
lubridate::now()
```

    [1] "2025-06-16 18:36:58 UTC"

(Analise dos dados aqui)

``` r
# sc <- spark_connect(method = "databricks_connect")
```

Problemas de uma pessoa ter que atualizar todo dia:

-   A pessoa pode estar ausente
-   A pessoa pode esquecer de rodar alguma etapa
-   A pessoa pode errar
-   A pessoa responsavel pode ter saido da area ou da empresa

Solucao proposta: automatizar a rodagem quando - Ou o documento for
alterado (sofrer alguma mudanca/melhoria) - Ou agendado para rodar todo
dia ou todo mes (ou periodicamente)

Github Actions

Agora este documento tem um secao a mais
