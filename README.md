# Mineração de Dados Eleitorais 2026 — Grupo 3

Projeto desenvolvido na disciplina de **Mineração de Dados**, utilizando dados públicos do TSE referentes às Eleições 2026.

## 📌 Recorte do grupo

**Cargo:** Deputado Federal
**Região:** Sul
**Estados:** Paraná (PR), Rio Grande do Sul (RS) e Santa Catarina (SC)

## 📂 Fase 0 — Preparação dos Dados

O notebook `00_preparacao_dados.ipynb` realiza a preparação da base que será utilizada durante o projeto.

Nesta etapa foram realizados:

* obtenção e leitura dos dados brutos de candidaturas e bens declarados do TSE;
* adaptação do filtro para considerar todas as UFs da Região Sul (`PR`, `RS` e `SC`);
* filtro dos candidatos ao cargo de **Deputado Federal**;
* tratamento e preparação das informações;
* processamento dos bens declarados;
* aplicação das validações previstas no notebook;
* geração do **CSV final preparado**.

O CSV disponível na pasta `dados/` representa a versão preparada da base e será utilizado como entrada para as próximas fases do projeto.

## 📊 Próxima etapa — Fase 1

A próxima etapa é a **Análise Descritiva dos Dados**.

Serão analisados:

* distribuições das variáveis numéricas, como idade e patrimônio;
* identificação de outliers;
* contagens e proporções das variáveis categóricas;
* correlações entre variáveis numéricas;
* análises bivariadas e cruzamentos;
* comparação dos candidatos entre **PR, RS e SC**.

Além dos gráficos e resultados estatísticos, serão registradas observações sobre os principais padrões, diferenças e possíveis dados atípicos encontrados.

As etapas seguintes do projeto serão **clusterização, regras de associação e detecção de anomalias**.
