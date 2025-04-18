# TABELAS DE APOIO

## O que são as tabelas de apoio?

As **tabelas de apoio** são conjuntos de dados organizados em formato CSV (Comma-Separated Values), utilizados como base auxiliar em análises e visualizações. Essas tabelas funcionam como referência para enriquecer, estruturar e dar suporte à manipulação de dados em diferentes contextos. Elas são aplicadas para:

- **Gerar cálculos**: com dados básicos que possibilitam o desenvolvimento de indicadores e métricas customizadas.
- **Aplicar filtros**: segmentando informações conforme critérios como localização geográfica, faixa populacional, ou período.
- **Elaborar mapas**: por meio de códigos geográficos, como os do IBGE, permitindo representações espaciais detalhadas.
- **Construir visualizações**: como gráficos, painéis interativos (dashboards) e relatórios.

Essas tabelas são essenciais para garantir consistência e precisão em projetos de análise de dados, contribuindo para uma melhor compreensão e tomada de decisão baseada em evidências.

---

## 1. Arquivo: `tabela-apoio-brasil-censo2022-5570municipios.csv`

| **Campo**             | **Descrição** |
|------------------------|---------------|
| `ID`                  | Número sequencial |
| `codmun7txt`          | Código municipal do IBGE com 7 dígitos em formato Texto |
| `codmun6num`          | Código municipal do IBGE com 6 dígitos em formato Numérico |
| `codmun7num`          | Código municipal do IBGE com 7 dígitos em formato Numérico |
| `macroregiao`         | Macro Região de Saúde: <br>1. Norte <br>2. Nordeste <br>3. Sudeste <br>4. Sul <br>5. Centro-Oeste |
| `uf-regiao`           | Unidade Federada |
| `municipio-regiao`    | Nome do Município |
| `codregsaude`         | Código das regiões de saúde |
| `censo2022`           | População censitária do IBGE, por município |
| `faixapop`            | Faixa populacional: <br>1 - Até 5.000 <br>2 - 5.001 até 10.000 <br>3 - 10.001 até 20.000 <br>4 - 20.001 até 50.000 <br>5 - 50.001 até 100.000 <br>6 - 100.001 até 500.000 <br>7 - Maior que 500.000 |
| `ufregsaude`          | Nome da região de saúde com a macrorregião e unidade federada correspondente |

---

## 2. Arquivo: `tabela-apoio-brasil-nascidosvivos-5570municipios.csv`

| **Campo**                   | **Descrição** |
|-----------------------------|---------------|
| `ID`                        | Número sequencial |
| `codmun6num`                | Código municipal do IBGE com 6 dígitos em formato Numérico |
| `municipio-residencia-mae`  | Município de residência da mãe da criança|
| `nasc2014`                  | Total de nascidos vivos em 2014 |
| `nasc2015`                  | Total de nascidos vivos em 2015 |
| `nasc2016`                  | Total de nascidos vivos em 2016 |
| `nasc2017`                  | Total de nascidos vivos em 2017 |
| `nasc2018`                  | Total de nascidos vivos em 2018 |
| `nasc2019`                  | Total de nascidos vivos em 2019 |
| `nasc2020`                  | Total de nascidos vivos em 2020 |
| `nasc2021`                  | Total de nascidos vivos em 2021 |
| `nasc2022`                  | Total de nascidos vivos em 2022 |
| `nasc2023`                  | Total de nascidos vivos em 2023 |
| `media14a23`                | Média de nascidos vivos de 2014 a 2023 por município |

## 3. Arquivo: `tabela-apoio-brasil-nascidosanomaliacongenita-5570municipios.csv`

| **Campo**                   | **Descrição** |
|-----------------------------|---------------|
| `ID`                        | Número sequencial |
| `codmun6num`                | Código municipal do IBGE com 6 dígitos em formato Numérico |
| `municipnascaconalia`       | Município de residência da mãe da criança com anomalia congênita  |
| `anomcong2014`                  | Total de nascidos vivos com anomalia em 2014 |
| `anomcong2015`                  | Total de nascidos vivos com anomalia em 2015 |
| `anomcong2016`                  | Total de nascidos vivos com anomalia em 2016 |
| `anomcong2017`                  | Total de nascidos vivos com anomalia em 2017 |
| `anomcong2018`                  | Total de nascidos vivos com anomalia em 2018 |
| `anomcong2019`                  | Total de nascidos vivos com anomalia em 2019 |
| `anomcong2020`                  | Total de nascidos vivos com anomalia em 2020 |
| `anomcong2021`                  | Total de nascidos vivos com anomalia em 2021 |
| `anomcong2022`                  | Total de nascidos vivos com anomalia em 2022 |
| `anomcong2023`                  | Total de nascidos vivos com anomalia em 2023 |

## 4. Arquivo: `tabela-apoio-brasil-mortalidadegeral-5570municipios.csv`

| **Campo**                   | **Descrição** |
|-----------------------------|---------------|
| `ID`                        | Número sequencial |
| `codmun6num`                | Código municipal do IBGE com 6 dígitos em formato Numérico |
| `municipioobito`            | Município de residência do óbito |
| `obito2014`                 | Total de óbitos gerais em 2014 |
| `obito2015`                 | Total de óbitos gerais em 2015 |
| `obito2016`                 | Total de óbitos gerais em 2016 |
| `obito2017`                 | Total de óbitos gerais em 2017 |
| `obito2018`                 | Total de óbitos gerais em 2018 |
| `obito2019`                 | Total de óbitos gerais em 2019 |
| `obito2020`                 | Total de óbitos gerais em 2020 |
| `obito2021`                 | Total de óbitos gerais em 2021 |
| `obito2022`                 | Total de óbitos gerais em 2022 |
| `obito2023`                 | Total de óbitos gerais em 2023 |
| `mediaobt14a23`             | Média de óbitos de 2014 a 2023 por município |
