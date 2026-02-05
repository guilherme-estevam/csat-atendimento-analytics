# 📁 Dados Processados — CSAT

> 🔖 **Status atual:** V2 do projeto  
> Esta versão inclui análises de CSAT segmentadas por **faixa de tempo de atendimento**, avaliando o impacto da duração no nível de satisfação.  
> Novas versões (V3+) incluirão análises adicionais, novas dimensões e refinamentos no processamento.

Esta pasta contém os **dados processados e consolidados** do projeto de análise de CSAT, derivados da base bruta localizada em `data/raw`.

Os arquivos aqui armazenados representam diferentes **versões do processamento e das análises**, evoluindo conforme novas métricas, dimensões e automações são adicionadas ao projeto.

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

- **Análises por Faixa de Tempo**  
  Segmentação dos atendimentos por duração, permitindo avaliar a relação entre tempo de atendimento e CSAT.

---

## 🔄 Versionamento

Cada arquivo representa uma **versão do processamento**, podendo evoluir com:

- Inclusão de novas métricas
- Novas segmentações e análises
- Melhorias no tratamento e organização dos dados
- Automatização do fluxo de atualização

As versões são identificadas:
- no **nome do arquivo** (ex: `csat_analysis_v2.xlsx`)
- e/ou documentadas no **histórico de versões** abaixo

---

## 🧩 Histórico de Versões

- **V2**  
  Inclusão da análise de CSAT por **faixa de tempo de atendimento**, avaliando se atendimentos mais longos impactam a satisfação do cliente.

- **V1**  
  Estrutura inicial do projeto, organização da base processada e consolidação das métricas principais de CSAT.

---

## 📌 Observações

- Os dados presentes nesta pasta **não devem ser tratados como dados brutos**
- Qualquer nova transformação deve partir da base localizada em `data/raw`
- O objetivo desta pasta é fornecer bases analíticas confiáveis para análise, exploração e visualização

---

📊 *Esta pasta centraliza o resultado do trabalho analítico do projeto de CSAT, servindo como base para análises, dashboards e evolução contínua do projeto.*
