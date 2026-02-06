# 📁 Dados Processados — CSAT

> 🔖 **Status atual:** **V3 do projeto**  
> Esta versão aprofunda a análise de CSAT, incorporando **cruzamentos entre canal de atendimento e faixa de tempo**, além da **distribuição das notas de satisfação** e da **geração de insights analíticos**.  
> Novas versões (V4+) incluirão automação, replicação via SQL e refinamentos adicionais.

Esta pasta contém os **dados processados e consolidados** do projeto de análise de CSAT, derivados da base bruta localizada em `data/raw`.

Os arquivos aqui armazenados representam diferentes **versões do processamento e das análises**, evoluindo conforme novas métricas, dimensões e níveis de maturidade analítica são adicionados ao projeto.

---

## 📄 Estrutura dos Arquivos

Os arquivos de dados processados seguem um padrão de organização por abas, contemplando as principais etapas do fluxo analítico:

- **raw_csat**  
  Cópia da base bruta utilizada como referência interna, garantindo rastreabilidade dos dados ao longo do processo.

- **processed_csat**  
  Base tratada, com padronização de datas, criação de colunas analíticas e preparação para análises.

- **csat_por_canal**  
  Análise de CSAT segmentada por canal de atendimento.

- **metrics**  
  Consolidação dos principais indicadores de satisfação e volume de atendimentos.

- **csat_canal_faixa_tempo**  
  Análise cruzada entre **canal de atendimento e faixa de tempo**, permitindo avaliar o impacto conjunto dessas dimensões no CSAT.

- **distribuicao_csat**  
  Distribuição das notas de CSAT, utilizada para avaliar a consistência da experiência do cliente e identificar concentração de avaliações negativas ou positivas.

- **insights_v3**  
  Interpretação analítica dos resultados, com conclusões orientadas ao negócio e identificação de pontos de atenção e oportunidades de melhoria.

---

## 🔄 Versionamento

Cada arquivo representa uma **versão evolutiva do processamento**, refletindo o amadurecimento das análises ao longo do projeto.

As versões podem evoluir com:
- Inclusão de novas métricas
- Novas segmentações e cruzamentos de dados
- Refinamentos no tratamento e organização das bases
- Evolução para automação e uso de SQL

As versões são identificadas:
- no **nome do arquivo** (ex: `csat_v1.xlsx`, `csat_v2.xlsx`, `csat_v3.xlsx`)
- e documentadas no **histórico de versões** abaixo

---

## 🧩 Histórico de Versões

- **V3**  
  Inclusão de análises avançadas, com cruzamento entre **canal de atendimento e faixa de tempo**, distribuição das notas de CSAT e geração de **insights analíticos** focados em leitura de negócio.

- **V2**  
  Inclusão da análise de CSAT por **faixa de tempo de atendimento**, avaliando se atendimentos mais longos impactam a satisfação do cliente.

- **V1**  
  Estrutura inicial do projeto, organização da base processada e consolidação das métricas principais de CSAT.

---

## 📌 Observações

- Os dados presentes nesta pasta **não devem ser tratados como dados brutos**
- Qualquer nova transformação deve partir da base localizada em `data/raw`
- O objetivo desta pasta é fornecer **bases analíticas confiáveis**, prontas para exploração, visualização e tomada de decisão

---

📊 *Esta pasta centraliza o resultado do trabalho analítico do projeto de CSAT, servindo como base para análises operacionais, insights estratégicos e evolução contínua do projeto.*
