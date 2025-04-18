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

# ---- # ---- # ----- # ---- # ---- # ----- # ---- # ---- # ----- # ---- # ---- # ----- # ---- # ---- # ----- # ---- # ---- # ----- # ---- # ---- # -----

#### Agrupamento dos tipos CNES por nível de complexidade assistencial  

> **Critério adotado**  
> O CNES não possui um campo “complexidade” fixo; a distribuição abaixo segue o enquadramento previsto na **PNAB 2017** para Atenção Primária, na **PNAES 2023** para Atenção Especializada e no **Regulamento Técnico da Rede de Urgência (Port. 2048/2002)** para serviços de alta densidade tecnológica, além das definições oficiais da Tabela CNES de Tipos de Estabelecimento【turn1view0】.  

---

### 1. Atenção Primária à Saúde (APS)  
| Código | Tipo de Estabelecimento |
|-------:|-------------------------|
| 01 | **Posto de Saúde** |
| 02 | **Centro de Saúde / Unidade Básica** |
| 22 | Consultório Isolado |
| 71 | Centro de Apoio à Saúde da Família (NASF/CASF) |
| 72 | Unidade de Atenção à Saúde Indígena (Polo‑base, UBSI) |
| 74 | Polo Academia da Saúde |
| 75 | Telessaúde (núcleo ou ponto) |
| 32 | Unidade Móvel Fluvial |
| 40 | Unidade Móvel Terrestre |
| 43 | Farmácia |
| 83 | Polo de Prevenção de Doenças, Agravos e Promoção da Saúde |
| 50 | Unidade de Vigilância em Saúde |  
**Referências:** PNAB 2017 – Port. 2.436/2017【turn2search0】; Tabela CNES【turn1view0】  

---

### 2. Média Complexidade (ambulatorial e hospitalar)  
| Código | Tipo de Estabelecimento |
|-------:|-------------------------|
| 04 | Policlínica |
| 36 | Clínica / Centro de Especialidade |
| 39 | Unidade de Apoio Diagnose e Terapia (SADT Isolado) |
| 15 | Unidade Mista |
| 62 | Hospital‑Dia – Isolado |
| 61 | Centro de Parto Normal – Isolado |
| 73 | Pronto Atendimento (UPA) |
| 20 | Pronto‑Socorro Geral |
| 21 | Pronto‑Socorro Especializado |
| 70 | Centro de Atenção Psicossocial (CAPS I‑III, AD) |
| 77 | Serviço de Atenção Domiciliar – Isolado (Home Care) |
| 78 | Unidade de Atenção em Regime Residencial |
| 79 | Oficina Ortopédica |  
**Referências:** PNAES 2023 – Port. 1.604/2023【turn4search0】; Port. 1600/2011 – Rede de Urgências【turn5search3】; Tabela CNES【turn1view0】

---

### 3. Alta Complexidade (alta densidade tecnológica / terciária)  
| Código | Tipo de Estabelecimento |
|-------:|-------------------------|
| 05 | Hospital Geral |
| 06 | Hospital Especializado |
| 69 | Centro de Atenção Hemoterápica e / ou Hematológica |
| 80 | Laboratório Central de Saúde Pública – LACEN |
| 42 | Unidade Móvel de Nível Pré‑Hospitalar em Urgência (SAMU) |
| 76 | Central de Regulação Médica das Urgências |
| 81 | Central de Regulação do Acesso |
| 82 | Central de Notificação, Captação e Distribuição de Órgãos (CNCDO) |
| 68 | Central / Secretaria de Gestão em Saúde |  
**Referências:** Regulamento Técnico de Urgência – Port. 2.048/2002【turn5search0】; Tabela CNES【turn1view0】

---

#### Observações importantes  
* Alguns estabelecimentos **transversais** (ex.: vigilância, gestão, regulação) não prestam assistência direta; foram alocados segundo o grau de tecnologia e articulação exigido.  
* A **atribuição de complexidade pode variar** quando o serviço opera dentro de redes regionais (por exemplo, um CAPS III com leitos 24 h pode compor alta complexidade em saúde mental).  
* Para análise de rede assistencial em sistemas de informação (SIH/SIA), utilize também o **código de serviço + classificação** do CNES, pois é nele que o nível de complexidade do **procedimento** é efetivamente registrado.
