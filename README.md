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



### Tipos de estabelecimentos de saúde no CNES  

| Código | Tipo de Estabelecimento | Conceito resumido* |
|--------|------------------------|--------------------|
| **01** | Posto de Saúde | Unidade básica com equipe de nível médio e presença eventual de médico. |
| **02** | Centro de Saúde / Unidade Básica | Atenção básica permanente nas especialidades essenciais, podendo ofertar SADT e pronto‑atendimento. |
| **04** | Policlínica | Atendimento ambulatorial multiprofissional, inclusive SADT e pronto‑atendimento. |
| **05** | Hospital Geral | Internação e urgência nas especialidades básicas; requer SADT de média complexidade. |
| **06** | Hospital Especializado | Internação em única especialidade ou área (ex.: oncologia, psiquiatria). |
| **15** | Unidade Mista | Combina serviços ambulatoriais e leitos de internação de baixa complexidade. |
| **20** | Pronto‑Socorro Geral | Unidade hospitalar de portas abertas para urgências em clínica geral/cirurgia. |
| **21** | Pronto‑Socorro Especializado | Urgência focada em uma especialidade (ex.: ortopedia, cardiologia). |
| **22** | Consultório Isolado | Sala isolada de atendimento médico, odontológico ou de outro profissional de saúde. |
| **32** | Unidade Móvel Fluvial | Barco/navio com consultórios e sala de curativos para áreas ribeirinhas. |
| **36** | Clínica / Centro de Especialidade | Atendimento ambulatorial em única especialidade (p. ex. CAPS, reabilitação). |
| **39** | SADT Isolado | Unidade de apoio diagnóstico/terapêutico não vinculada a hospital (lab., imagem, etc.). |
| **40** | Unidade Móvel Terrestre | Veículo equipado para assistência (inclui unidade odontológica móvel). |
| **42** | Unidade Móvel Pré‑Hospitalar | Viatura terrestre/aérea/hidro para atendimento de urgência pré‑hospitalar (SAMU). |
| **43** | Farmácia | Dispensação de medicamentos básicos, excepcionais ou de alto custo. |
| **50** | Unidade de Vigilância em Saúde | Ações de investigação, prevenção e controle de riscos epidemiológicos/sanitários. |
| **60** | Cooperativa/Empresa de Cessão | Administração de profissionais cooperados para atuação em saúde. |
| **61** | Centro de Parto Normal – Isolado | Unidade (intra‑ ou extra‑hospitalar) dedicada ao parto de baixo risco. |
| **62** | Hospital‑Dia – Isolado | Internação de curta permanência, intermediária entre ambulatório e hospital. |
| **68** | Central de Gestão em Saúde | Sede administrativa (Secretarias, operadoras, distritos) responsável por planejamento, regulação e logística. |
| **69** | Centro de Atenção Hemoterápica/Hematológica | Execução do ciclo do sangue (captação, processamento, transfusão). |
| **70** | Centro de Atenção Psicossocial (CAPS) | Cuidado em saúde mental de média complexidade, substitutivo à internação. |
| **71** | Centro de Apoio à Saúde da Família (CASF) | Núcleo multiprofissional de retaguarda para as equipes de Saúde da Família. |
| **72** | Unidade de Atenção à Saúde Indígena | Atenção básica integral em comunidades indígenas (UBSI, CASAI, polo‑base). |
| **73** | Pronto Atendimento (UPA) | Unidade autônoma 24 h que estabiliza urgências e decide remoção ou alta. |
| **74** | Polo Academia da Saúde | Espaço comunitário para práticas corporais, educação em saúde e lazer. |
| **75** | Telessaúde | Núcleo ou ponto de serviços remotos de apoio diagnóstico, educação ou regulação. |
| **76** | Central de Regulação Médica das Urgências | Coordena os fluxos assistenciais pré‑hospitalares (SAMU 192). |
| **77** | Serviço de Atenção Domiciliar – Isolado | Home care privado que presta assistência integral no domicílio. |
| **78** | Unidade de Atenção em Regime Residencial | Acolhimento residencial transitório para usuários de álcool/drogas (Rede RAPS). |
| **79** | Oficina Ortopédica | Confecciona, adapta e mantém órteses/próteses de locomoção. |
| **80** | Laboratório de Saúde Pública (LACEN) | Rede pública de laboratórios centrais (federal, estadual ou municipal). |
| **81** | Central de Regulação do Acesso | Avalia, processa e agenda solicitações de consultas, exames e internações. |
| **82** | Central de Notificação, Captação e Distribuição de Órgãos (CNCDO) | Coordena a doação e alocação de órgãos/tecidos para transplantes no estado. |
| **83** | Polo de Prevenção de Doenças e Agravos e Promoção da Saúde | Desenvolve ações de promoção da saúde e prevenção de agravos, individuais ou coletivas. |

\* Conceitos sintetizados a partir dos manuais técnicos do CNES e portarias vigentes. Para requisitos completos (subtipos, habilitações e bases legais) consulte a Ficha 01 de Identificação do CNES e as portarias SAS/MS correspondentes.

**Fontes principais**

- Manual de Tipos e Subtipos de Estabelecimentos de Saúde – CNES (versão atualizada, mar/ 2025) citeturn5view0turn8view0turn13view0  
- Instruções de Preenchimento – CNES Ficha 01 (atualização jan/ 2024 e mar/ 2025) citeturn14search3turn19search6turn20search4  
- Portarias SAS/MS nº 168/2016 (Central de Gestão), nº 530/2014 (CNCDO) e nº 1 482/2016 (Polo de Prevenção) citeturn19search9turn22search1turn21search0  
- Tabela on‑line “Tipo de Estabelecimento” (cnes2.datasus.gov.br) citeturn20search0turn23search0  
- FAQs da Wiki CNES sobre nova classificação (2023–2025) citeturn20search3turn21search2

Essas categorias orientam o cadastramento, a gestão dos serviços e a análise de rede assistencial no SUS.
