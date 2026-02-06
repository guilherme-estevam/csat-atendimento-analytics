# 📁 Dados Processados — CSAT

> 🔖 **Status atual:** V3 do projeto  
> Esta versão inclui análises de CSAT com **novas dimensões analíticas**, organização aprimorada das bases e a criação de uma **página dedicada de insights**, facilitando a interpretação dos resultados.  
> Versões futuras (V4+) poderão expandir métricas, granularidade e automações.

Esta pasta contém os **dados processados e consolidados** do projeto de análise de CSAT, derivados exclusivamente da base bruta localizada em `data/raw`.

Os arquivos aqui armazenados representam diferentes **versões do processamento e das análises**, evoluindo conforme novas métricas, dimensões e refinamentos são incorporados ao projeto.

---

## 📄 Arquivo Atual

- **`csat_analysis_v3.xlsx`**  
  Arquivo principal da versão V3, contendo todas as abas de dados tratados, análises, métricas consolidadas e insights.

---

## 🗂️ Estrutura Interna do Arquivo

O arquivo `csat_analysis_v3.xlsx` segue um padrão de organização por abas, contemplando as principais etapas do fluxo analítico:

- **raw_csat**  
  Cópia da base bruta utilizada como referência interna, garantindo rastreabilidade dos dados ao longo do processo.

- **processed_csat**  
  Base tratada, com:
  - padronização de datas  
  - criação de colunas analíticas  
  - preparação para análises e agregações

- **csat_por_canal**  
  Análise de CSAT segmentada por canal de atendimento.

- **metrics**  
  Consolidação dos principais indicadores:
  - CSAT médio  
  - volume de atendimentos  
  - taxas de avaliação

- **análises_por_faixa_tempo**  
  Segmentação dos atendimentos por duração, permitindo avaliar a relação entre tempo de atendimento e satisfação.

- **insights**  
  Página dedicada à interpretação dos dados, reunindo conclusões analíticas, padrões observados e direcionamentos para tomada de decisão.

---

## 🔄 Versionamento

Cada arquivo nesta pasta representa uma **versão evolutiva do processamento**, podendo incluir:

- novas métricas
- novas segmentações
- melhorias no tratamento dos dados
- reorganização estrutural
- expansão da camada analítica

As versões são identificadas:
- no **nome do arquivo** (ex: `csat_analysis_v3.xlsx`)
- e documentadas no histórico abaixo

---

## 🧩 Histórico de Versões

- **V3**  
  Inclusão de novas dimensões analíticas, reorganização das abas e criação de uma página dedicada de **insights**, facilitando a leitura executiva dos resultados.

- **V2**  
  Inclusão da análise de CSAT por **faixa de tempo de atendimento**, avaliando o impacto da duração na satisfação do cliente.

- **V1**  
  Estrutura inicial do projeto, organização da base processada e consolidação das métricas principais de CSAT.

---

## 📌 Observações

- Os dados desta pasta **não devem ser tratados como dados brutos**
- Qualquer nova transformação deve partir da base em `data/raw`
- Esta pasta representa a **camada analítica consolidada** do projeto

---

📊 *Esta pasta concentra os resultados do processamento e da análise de CSAT, servindo como base para exploração, visualização, insights e evolução contínua do projeto.*
