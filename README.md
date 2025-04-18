# TABELAS DE APOIO

## O que são as tabelas de apoio?

As **tabelas de apoio** são conjuntos de dados organizados em formato CSV (Comma-Separated Values) que servem como referência para facilitar e agilizar análises de dados. Elas são utilizadas para:

- **Gerar cálculos**: fornecendo informações básicas que podem ser combinadas ou processadas para extrair novos indicadores e métricas.
- **Aplicar filtros**: permitindo segmentar ou categorizar dados de acordo com critérios específicos, como localização geográfica, faixa populacional, entre outros.
- **Elaborar mapas**: oferecendo chaves e códigos (como o código municipal do IBGE) que possibilitam a criação de visualizações geográficas.
- **Criar outras visualizações**: como gráficos, dashboards e relatórios interativos.

Essas tabelas são fundamentais para enriquecer e estruturar análises, promovendo uma melhor compreensão dos dados e auxiliando na tomada de decisões baseadas em informações concretas.

## 1. Arquivo: `tabela-apoio-brasil-censo2022-5570municipios.csv`

| **Campo**         | **Descrição** |
|-------------------|---------------|
| `ID`              | Número sequencial |
| `codmun7txt`      | Código municipal do IBGE com 7 dígitos em formato Texto |
| `codmun6num`      | Código municipal do IBGE com 6 dígitos em formato Numérico |
| `codmun7num`      | Código municipal do IBGE com 7 dígitos em formato Numérico |
| `macroregiao`     | Macro Região de Saúde: <br>1. Norte <br>2. Nordeste <br>3. Sudeste <br>4. Sul <br>5. Centro-Oeste |
| `uf-regiao`       | Unidade Federada |
| `municipio-regiao`| Nome do Município |
| `codregsaude`     | Código das regiões de saúde |
| `censo2022`       | População censitária do IBGE, por município |
| `faixapop`        | Faixa populacional: <br>1 - Até 5.000 <br>2 - 5.001 até 10.000 <br>3 - 10.001 até 20.000 <br>4 - 20.001 até 50.000 <br>5 - 50.001 até 100.000 <br>6 - 100.001 até 500.000 <br>7 - Maior que 500.000 |
| `ufregsaude`      | Nome da região de saúde com a macrorregião e unidade federada correspondente |

