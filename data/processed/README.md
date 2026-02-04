# 📁 Dados Processados — CSAT

Esta pasta contém os **dados processados e consolidados** do projeto de análise de CSAT, derivados da base bruta localizada em `data/raw`.

Os arquivos aqui armazenados representam diferentes **versões do processamento e das análises**, evoluindo conforme novas métricas, dimensões e automações são adicionadas ao projeto.

---

## 📄 Estrutura dos Arquivos

Os arquivos de dados processados seguem um padrão de organização por abas, contemplando as principais etapas do fluxo analítico:

- **raw_csat**  
  Cópia da base bruta utilizada como referência interna, garantindo rastreabilidade dos dados.

- **processed_csat**  
  Base tratada, com padronização de dados e criação de colunas analíticas.

- **csat_por_canal**  
  Análises segmentadas por canal de atendimento.

- **metrics**  
  Consolidação dos principais indicadores operacionais e de satisfação.

---

## 🔄 Versionamento

Cada arquivo representa uma **versão do processamento**, podendo evoluir com:

- Inclusão de novas métricas
- Novas segmentações e análises
- Melhorias no tratamento dos dados
- Automatização do fluxo de atualização

As versões são identificadas:
- no nome do arquivo, quando aplicável
- ou na documentação do projeto (README principal)

---

## 📌 Observações

- Os dados presentes nesta pasta **não devem ser tratados como dados brutos**
- Qualquer nova transformação deve partir da base localizada em `data/raw`
- O objetivo desta pasta é fornecer bases analíticas confiáveis para análise e visualização

---

📊 *Esta pasta centraliza o resultado do trabalho analítico do projeto de CSAT, servindo como base para análises, dashboards e evolução contínua do projeto.*
