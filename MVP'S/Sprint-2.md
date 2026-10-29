# 📌 MVP - Pathlog | Sprint 2

> **Projeto:** Análise de Acidentes com Veículos Pesados nas Estradas Brasileiras  
> **Equipe:** Pathlog  
> **Ano:** 2026

---

## 📑 Índice

- [🎯 Objetivo do MVP](#-objetivo-do-mvp)
- [💡 Descrição da Solução](#-descrição-da-solução)
- [👥 Personas](#-personas)
- [📋 Histórias de Usuário](#-histórias-de-usuário)
- [🛠️ Funcionalidades da Sprint 2](#️-funcionalidades-da-sprint-2)
- [✅ Critérios de Aceitação](#-critérios-de-aceitação)
- [📊 Dados e Indicadores](#-dados-e-indicadores)
- [📦 Entregas da Sprint 2](#-entregas-da-sprint-2)
- [🔄 Relação com as Sprints](#-relação-com-as-sprints)
- [📍 Situação Atual](#-situação-atual)

---

## 🎯 Objetivo do MVP

A Sprint 2 tem como objetivo evoluir o MVP do Pathlog, ampliando as possibilidades de análise dos acidentes envolvendo veículos pesados nas rodovias brasileiras.

Nesta etapa, o foco está na implementação de filtros interativos no Power BI, na comparação entre os dados da Polícia Rodoviária Federal (PRF) e do DATASUS e na apresentação do problema que motivou o desenvolvimento do projeto.

A proposta é tornar a análise mais dinâmica, facilitando a identificação de padrões e diferenças entre regiões e períodos.

---

## 💡 Descrição da Solução

O Pathlog utiliza dados públicos para desenvolver um dashboard interativo capaz de apresentar informações sobre acidentes, mortes, população e frota de veículos.

Na Sprint 2, a solução será aprimorada por meio de três frentes principais:

- **🔎 Filtros interativos:** permitir que o usuário selecione períodos, regiões e categorias de veículos para explorar os dados.
- **📈 Comparação entre fontes:** apresentar informações da PRF e do DATASUS, considerando suas diferenças de abrangência e metodologia.
- **🎥 Apresentação do problema:** produzir um vídeo que explique a necessidade identificada, os objetivos do projeto e a solução proposta.

---

## 👥 Personas

| Persona | Necessidade | Benefício do MVP |
|---|---|---|
| 📊 Analista de dados | Investigar padrões e comparar indicadores. | Visualizar os dados com filtros e gráficos interativos. |
| 🚛 Profissional ligado ao transporte rodoviário | Compreender melhor o cenário dos acidentes envolvendo veículos pesados. | Identificar informações relevantes sobre acidentes e mortalidade. |
| 🏢 Parceiro do projeto | Compreender o problema e acompanhar a proposta de solução. | Consultar os resultados e entender a finalidade do dashboard. |

---

## 📋 Histórias de Usuário

| ID | Prioridade | História de Usuário | Estimativa | Sprint |
|---|---|---|---:|---:|
| US4 | 🔴 Alta | Como usuário, quero filtrar os dados por ano, região, tipo de veículo e gravidade, para realizar análises específicas. | 8 | 2 |
| US5 | 🔴 Alta | Como analista, quero comparar os dados da PRF com os óbitos registrados pelo DATASUS, para compreender as diferenças entre as fontes. | 8 | 2 |
| US12 | 🔴 Alta | Como parceiro do projeto, quero assistir a uma apresentação do problema e da necessidade identificada, para compreender a relevância da solução proposta. | 3 | 2 |

---

## 🛠️ Funcionalidades da Sprint 2

### 🔎 1. Filtros Interativos

Implementar filtros no dashboard para facilitar a consulta e a exploração dos dados.

**Funcionalidades previstas:**

- Seleção do ano.
- Filtragem por região e unidade federativa.
- Seleção do tipo de veículo.
- Filtragem por gravidade, conforme a disponibilidade dos dados.
- Atualização dos gráficos e indicadores de acordo com as seleções realizadas.

### 📈 2. Comparação PRF × DATASUS

Desenvolver visualizações que permitam analisar os dados provenientes das duas fontes.

**Funcionalidades previstas:**

- Comparação dos registros por ano e unidade federativa.
- Visualização dos acidentes e das mortes registrados pela PRF.
- Apresentação dos óbitos por acidentes de transporte registrados pelo DATASUS.
- Identificação das diferenças entre as fontes.
- Documentação das limitações da comparação.

> ⚠️ **Atenção:** os dados da PRF e do DATASUS não representam necessariamente o mesmo conjunto de ocorrências. A PRF registra acidentes em rodovias federais, enquanto o DATASUS abrange óbitos por acidentes de transporte registrados no sistema de saúde. Por isso, os valores devem ser interpretados de acordo com a abrangência de cada base.

### 🎥 3. Vídeo de Apresentação

Produzir um vídeo explicando o problema abordado pelo Pathlog e a necessidade que motivou o desenvolvimento do MVP.

**O vídeo deverá apresentar:**

- O problema dos acidentes envolvendo veículos pesados.
- A necessidade identificada pelo parceiro.
- Os objetivos do projeto.
- A proposta de solução.
- A contribuição esperada do dashboard.

---

## ✅ Critérios de Aceitação

### US4 — Filtros Interativos

- [ ] Os filtros devem permitir selecionar os critérios disponíveis.
- [ ] Os gráficos e indicadores devem responder às seleções.
- [ ] As informações devem permanecer consistentes durante a filtragem.
- [ ] A navegação deve permitir explorar os dados de maneira simples.

### US5 — Comparação PRF × DATASUS

- [ ] Os dados devem estar organizados para permitir a comparação por ano e unidade federativa.
- [ ] As visualizações devem identificar claramente a fonte de cada indicador.
- [ ] As diferenças metodológicas devem ser documentadas.
- [ ] A análise não deve tratar os indicadores como medidas diretamente equivalentes.
- [ ] Os resultados devem ser coerentes com as bases utilizadas.

### US12 — Vídeo de Apresentação

- [ ] O vídeo deve explicar o problema abordado.
- [ ] A necessidade do parceiro deve ser apresentada com clareza.
- [ ] Os objetivos e a proposta do Pathlog devem estar presentes.
- [ ] O conteúdo deve ser coerente com o desenvolvimento do projeto.

---

## 📊 Dados e Indicadores

A Sprint 2 dará continuidade à utilização das bases públicas organizadas durante a Sprint 1.

| Fonte | Dados utilizados | Finalidade |
|---|---|---|
| 🚔 PRF/DATATRAN | Acidentes e mortes em rodovias federais. | Analisar os registros de acidentes rodoviários. |
| 🏥 DATASUS | Óbitos por acidentes de transporte. | Ampliar a análise da mortalidade no trânsito. |
| 👥 IBGE | População por unidade federativa e ano. | Contextualizar os indicadores populacionais. |
| 🚗 SENATRAN | Frota de veículos por unidade federativa e ano. | Relacionar os acidentes à dimensão da frota. |

**Indicadores considerados:**

- Número de acidentes registrados pela PRF.
- Número de mortes registradas pela PRF.
- Número de óbitos por acidentes de transporte registrados pelo DATASUS.
- Mortes por 100 mil habitantes.
- Acidentes por 10 mil veículos.

> ℹ️ Os indicadores devem manter suas respectivas fontes e definições. Diferenças de período, abrangência e metodologia precisam ser consideradas na interpretação dos resultados.

---

## 📦 Entregas da Sprint 2

| Entrega | Descrição | Status |
|---|---|---|
| 🔎 Filtros do dashboard | Implementação de filtros interativos para explorar os dados. | Em andamento |
| 📈 Comparação PRF × DATASUS | Desenvolvimento de visualizações comparativas e análise das diferenças entre as fontes. | Em andamento |
| 🎥 Vídeo de apresentação | Produção de material audiovisual sobre o problema e a necessidade do parceiro. | Em andamento |
| 📝 Documentação | Registro das alterações, funcionalidades e resultados no GitHub. | Em andamento |

---

## 🔄 Relação com as Sprints

| Sprint | Objetivo principal | Status |
|---|---|---|
| Sprint 1 | Estruturar os dados e desenvolver a primeira versão do dashboard. | Concluída / em finalização |
| Sprint 2 | Implementar filtros, comparar PRF e DATASUS e apresentar o problema do projeto. | Em andamento |
| Sprint 3 | Aprimorar a interface, desenvolver análises temporais e preparar a entrega final do MVP. | Não iniciado |

---

## 📍 Situação Atual

A Sprint 2 representa a evolução do dashboard desenvolvido na etapa anterior. O foco é ampliar a interação do usuário com os dados, desenvolver a comparação entre as fontes e apresentar de maneira clara o problema que o projeto busca abordar.

As entregas desta etapa servirão de base para a Sprint 3, na qual serão realizados os aprimoramentos finais da interface, das análises e da documentação.

---

**🚛 PATHLOG — Análise de Acidentes com Veículos Pesados nas Estradas Brasileiras**

*Dados para compreender os acidentes. Informação para apoiar a segurança viária.*

**Ano:** 2026
