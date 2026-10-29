# 🚛 Back_Log — Pathlog

# 📚 Aprendizado por Projeto Integrado (API)

## 📑 Índice

- [Projeto (API)](#projeto-api)
- [Equipe](#equipe)
- [Objetivo do Projeto](#objetivo-do-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Product Backlog](#product-backlog)
- [Entregas da Sprint 1](#entregas-da-sprint-1)
- [Entregas da Sprint 2](#entregas-da-sprint-2)
- [Registro das Sprints](#registro-das-sprints)
- [Situação Atual](#situação-atual)

---

# 🚀 Projeto (API)

Projeto pedagógico alicerçado na Metodologia API para ensino-aprendizado focado no desenvolvimento de competências e fundamentado nos pilares de aprendizado com problemas reais (RPBL), validação externa e mentalidade ágil.

O projeto utiliza estratégias para entender o problema, conceber uma solução viável, desenvolver e implementar o MVP, seguido de sua operação (CDIO).

Os resultados dos projetos devem obedecer ao Aviso Legal disponível no site da Fatec SJC, com definição das datas do kickoff e das Sprints.

## 🚛 Pathlog — Análise de Acidentes com Veículos Pesados nas Estradas Brasileiras

O Pathlog tem como objetivo organizar, tratar, integrar e visualizar dados relacionados à segurança viária no Brasil, com foco na análise de acidentes envolvendo veículos pesados.

A solução utiliza dados públicos para desenvolver indicadores e visualizações que permitam analisar acidentes, mortes, feridos, frota de veículos e população, facilitando a identificação de padrões geográficos e temporais.

---

# 👥 Equipe

| Função | Nome | LinkedIn & GitHub |
|---|---|---|
| Product Owner | Arthur Medeiro | GitHub |
| Scrum Master | Gustavo Oliveira | GitHub |
| Team Member | Gustavo Nilfran | GitHub |
| Team Member | Pedro Henrique | GitHub |

**Orientadores:** Prof. Bastos e Coordenador Marcus Nascimento.

---

# 🎯 Objetivo do Projeto

O projeto **Pathlog — Análise de Acidentes com Veículos Pesados nas Estradas Brasileiras** busca desenvolver uma solução de Business Intelligence capaz de transformar bases públicas de dados em informações úteis para a análise da segurança viária.

A solução permite trabalhar com informações sobre:

- 🚛 Acidentes envolvendo veículos pesados;
- 🚑 Mortes e feridos registrados em acidentes;
- 🚗 Frota de veículos por unidade federativa;
- 👥 População por estado e ano;
- 🗺️ Distribuição geográfica dos acidentes;
- 📊 Indicadores de segurança viária;
- 📈 Evolução dos registros ao longo dos anos.

O projeto está sendo desenvolvido em etapas, com entregas organizadas em três Sprints. A primeira etapa concentrou-se no tratamento e na integração dos dados e na criação da primeira versão do dashboard. A segunda busca ampliar as possibilidades de análise, implementar filtros e comparar informações provenientes de diferentes fontes.

---

# 🛠️ Tecnologias Utilizadas

- 🐍 **Python:** tratamento, limpeza, classificação e integração dos dados.
- 📓 **Google Colab:** execução dos códigos de processamento e análise.
- 📊 **Microsoft Power BI:** criação do dashboard, indicadores e visualizações interativas.
- 📈 **R:** apoio ao processamento e à análise dos dados.
- 🐙 **GitHub:** versionamento de arquivos, documentação e acompanhamento das entregas.
- 📝 **Microsoft Office 365:** elaboração de documentos e apresentações.
- 🎨 **Canva:** criação de materiais visuais e de apresentação.

---

# 📋 Product Backlog

| Rank | Prioridade | User Story | Estimativa (Story Points) | Sprint | Status | Requisito do Parceiro |
|---:|---|---|---:|---:|---|---|
| 1 | Alta | **Visualização Nacional** — Como pesquisador de segurança viária, quero visualizar dados nacionais de frota, população, mortes e sinistros em gráficos e mapas, para identificar tendências gerais. | 8 | 1 | Concluído | RN.P.1, RN.P.3 |
| 2 | Alta | **Visualização Estadual** — Como gestor estadual de trânsito, quero acessar métricas específicas do meu estado, para comparar indicadores locais com a média nacional. | 5 | 1 | Concluído | RN.P.3 |
| 3 | Alta | **Indicadores-Chave** — Como analista de dados, quero calcular mortalidade por 100 mil habitantes e sinistros por 10 mil veículos, para comparar indicadores de segurança viária. | 8 | 1 | Concluído | RN.P.1, RN.P.2 |
| 4 | Alta | **Filtros Interativos** — Como usuário da plataforma, quero aplicar filtros por tipo de veículo, região, ano e gravidade do sinistro, para explorar os dados de acordo com meus critérios. | 13 | 2 | Em andamento | RN.P.3, RN.P.5 |
| 5 | Média | **Filtro Cruzado Saúde/Transporte** — Como pesquisador acadêmico, quero cruzar dados de saúde do DATASUS com dados de acidentes da PRF, para ampliar a análise da mortalidade no trânsito. | 20 | 2 | Em andamento | RN.P.1, RN.P.2 |
| 6 | Média | **Análise de Padrões de Descanso** — Como especialista em logística, quero visualizar a distância entre pontos de parada de descanso e locais de sinistros, para investigar possíveis riscos relacionados à fadiga. | 13 | 2 | Não iniciado | RN.P.2 |
| 7 | Média | **Evolução Temporal** — Como formulador de políticas públicas, quero analisar a evolução dos indicadores de segurança viária entre 2015 e 2025, para identificar tendências. | 8 | 3 | Não iniciado | RN.P.1, RN.P.3 |
| 8 | Baixa | **Interface Intuitiva** — Como usuário final, quero acessar informações com poucos cliques, para facilitar a navegação e reduzir o tempo de análise. | 5 | 3 | Não iniciado | RN.P.5 |
| 9 | Baixa | **Responsividade** — Como gestor em campo, quero acessar o dashboard em dispositivos móveis, para consultar os indicadores de forma prática. | 8 | 3 | Não iniciado | RN.P.6 |
| 10 | Baixa | **Documentação Técnica** — Como desenvolvedor, quero ter scripts de limpeza e modelagem documentados em Python, para garantir reprodutibilidade e transparência. | 3 | 3 | Não iniciado | RN.P.2, RN.P.4 |
| 11 | Alta | **Apresentação do Problema** — Como parceiro do projeto, quero conhecer o problema identificado e a necessidade que motivou o Pathlog, para compreender a relevância da solução proposta. | 3 | 2 | Em andamento | Apresentação do problema e da proposta de solução |

> **Observação:** os status representam o planejamento registrado para o projeto e devem ser atualizados conforme as atividades forem concluídas. As estimativas originais do backlog foram preservadas; a nova história de apresentação foi acrescentada separadamente.

---

# 📦 Entregas da Sprint 1

Durante a Sprint 1, foram realizadas as principais atividades de preparação dos dados e desenvolvimento da primeira versão da solução.

| Atividade | Status |
|---|---|
| Tratamento das bases PRF/DATATRAN | ✅ Concluído |
| Organização dos dados de 2015 a 2025 | ✅ Concluído |
| Padronização dos registros de acidentes | ✅ Concluído |
| Classificação dos tipos de veículos | ✅ Concluído |
| Preparação da base de veículos pesados | ✅ Concluído |
| Tratamento dos dados do DATASUS | ✅ Concluído |
| Tratamento dos dados populacionais do IBGE | ✅ Concluído |
| Tratamento dos dados de frota do SENATRAN | ✅ Concluído |
| Integração das bases por UF e ano | ✅ Concluído |
| Criação dos indicadores principais | ✅ Concluído |
| Validação das bases | ✅ Concluído |
| Preparação da base consolidada para o Power BI | ✅ Concluído |
| Desenvolvimento da primeira versão do dashboard | ✅ Concluído |

### 📊 Resultado da Sprint 1

A integração foi estruturada principalmente pela combinação de unidade federativa (UF) e ano, considerando 27 unidades federativas ao longo de 11 anos.

**27 UFs × 11 anos = 297 registros**

A base consolidada reúne informações para analisar acidentes, mortes, população e frota, servindo como estrutura para as funcionalidades das próximas Sprints.

---

# 🚧 Entregas da Sprint 2

A Sprint 2 tem como foco aprimorar o dashboard e ampliar as possibilidades de análise dos acidentes envolvendo veículos pesados.

| Atividade | Descrição | Status |
|---|---|---|
| 🔎 Filtros interativos | Implementar filtros por ano, região, tipo de veículo e gravidade, conforme a disponibilidade dos dados. | Em andamento |
| 📊 Comparação PRF × DATASUS | Desenvolver visualizações para analisar os registros da PRF e os óbitos por acidentes de transporte do DATASUS. | Em andamento |
| 🧪 Validação das fontes | Verificar a consistência dos dados e documentar diferenças de abrangência e metodologia. | Em andamento |
| 🎥 Vídeo de apresentação | Apresentar o problema, a necessidade do parceiro e a proposta de solução do Pathlog. | Em andamento |
| 📝 Documentação no GitHub | Registrar as alterações, as funcionalidades desenvolvidas e os resultados da Sprint. | Em andamento |

## 🔎 Filtros Interativos

A implementação dos filtros deverá permitir que o usuário explore os dados de acordo com diferentes critérios, facilitando a análise dos acidentes.

**Critérios previstos:**

- [ ] Selecionar o ano analisado.
- [ ] Filtrar os dados por região e unidade federativa, quando aplicável.
- [ ] Selecionar o tipo de veículo.
- [ ] Filtrar por gravidade, conforme os campos disponíveis.
- [ ] Atualizar gráficos e indicadores de acordo com as seleções realizadas.

## 📊 Comparação entre PRF e DATASUS

A comparação busca ampliar a análise da mortalidade no trânsito por meio de informações provenientes de diferentes fontes públicas.

**Critérios previstos:**

- [ ] Organizar os dados por ano e unidade federativa.
- [ ] Apresentar visualizações comparativas.
- [ ] Identificar as diferenças entre as fontes.
- [ ] Informar a origem dos dados utilizados.
- [ ] Documentar as limitações da comparação.

> ⚠️ **Importante:** os dados da PRF se referem a acidentes registrados em rodovias federais, enquanto o DATASUS contempla óbitos por acidentes de transporte registrados no sistema de saúde. As duas bases possuem abrangências diferentes e não devem ser tratadas como medidas diretamente equivalentes.

## 🎥 Vídeo de Apresentação

A produção do vídeo deverá apresentar:

- [ ] O problema dos acidentes envolvendo veículos pesados.
- [ ] A necessidade identificada pelo parceiro.
- [ ] Os objetivos do Pathlog.
- [ ] A solução proposta pelo projeto.
- [ ] A contribuição esperada do dashboard.

---

# 🗓️ Registro das Sprints

| Sprint | Previsão | Status | Principais Entregas |
|---|---|---|---|
| Sprint 01 | 01/10/2026 | Concluída / em finalização | Tratamento das bases PRF, DATASUS, IBGE e SENATRAN; integração dos dados; criação de indicadores; validação; primeira versão do Power BI. |
| Sprint 02 | 29/10/2026 | Em andamento | Filtros interativos; comparação PRF × DATASUS; validação das fontes; vídeo de apresentação do problema. |
| Sprint 03 | 26/11/2026 | Não iniciado | Evolução temporal aprofundada; aprimoramento da interface; responsividade; documentação técnica e finalização do MVP. |
| Feira de Soluções | 03/12/2026 | Não iniciado | Apresentação final do projeto e demonstração da solução. |

---

# 📍 Situação Atual

## ✅ Sprint 1

A Sprint 1 encontra-se concluída / em finalização, com as bases de dados tratadas e organizadas e a primeira versão do dashboard desenvolvida.

As principais fontes utilizadas foram:

- PRF / DATATRAN;
- DATASUS;
- IBGE;
- SENATRAN.

A integração foi estruturada principalmente por **UF + ano**, resultando em 297 registros correspondentes a 27 unidades federativas e 11 anos.

O resultado dessa etapa é uma base consolidada que permite analisar indicadores relacionados a acidentes, mortes, população e frota de veículos.

## 🚧 Sprint 2

A Sprint 2 está planejada para ampliar as funcionalidades do dashboard e tornar a exploração dos dados mais flexível.

As principais frentes desta etapa são:

- Implementação de filtros interativos;
- Comparação entre os dados da PRF e do DATASUS;
- Validação das informações e documentação das limitações;
- Produção de vídeo sobre o problema e a necessidade do parceiro.

A comparação entre as fontes exige atenção às diferenças de abrangência e metodologia, principalmente porque os registros de acidentes da PRF não correspondem diretamente ao conjunto de óbitos registrados pelo DATASUS.

## 🔜 Próximas Etapas

Na Sprint 3, o projeto deverá avançar para:

- 📈 Análise da evolução temporal dos indicadores;
- 🖥️ Aprimoramento da interface e da navegação;
- 📱 Melhorias de responsividade;
- 🧪 Validação final dos dados e indicadores;
- 📝 Organização da documentação técnica;
- 🎤 Preparação da apresentação para a Feira de Soluções.

---

## 🚛 PATHLOG

**Análise de Acidentes com Veículos Pesados nas Estradas Brasileiras**

*Dados para compreender os acidentes. Informação para apoiar a segurança viária.*

**2026 — Fatec São José dos Campos**
