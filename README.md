# Back_Log

# Aprendizado por Projeto Integrado (API)

## Índice

- [Objetivo do Projeto](#objetivo-do-projeto)
- [Equipe](#equipe)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Product Backlog](#product-backlog)
- [Registro das Sprints](#registro-das-sprints)
- [Situação Atual](#situação-atual)

---

# Projeto (API)

Projeto pedagógico alicerçado na Metodologia API para ensino-aprendizado focado no desenvolvimento de competências e fundamentado nos pilares de aprendizado com problemas reais (RPBL), validação externa e mentalidade ágil.

O projeto utiliza estratégias para entender o problema, conceber uma solução viável, desenvolver e implementar o MVP, seguido de sua operação (CDIO).

Os resultados dos projetos devem obedecer ao Aviso Legal disponível no site da Fatec SJC, com definição das datas do kickoff e das Sprints.

---

# Equipe

| Função | Nome | LinkedIn & GitHub |
|---|---|---|
| Product Owner | Arthur Medeiro | GitHub: 
| Scrum Master | Gustavo Oliveira | GitHub |
| Team Member | Gustavo Nilfran | GitHub |
| Team Member | Pedro Henrique | GitHub |

---

# Objetivo do Projeto

O projeto **Pathlog — Análise de Acidentes com Veículos Pesados nas Estradas Brasileiras** tem como objetivo organizar, tratar, integrar e visualizar dados relacionados à segurança viária no Brasil.

A solução busca facilitar a análise de informações sobre:

- Acidentes;
- Mortes;
- Feridos;
- Frota de veículos;
- População;
- Tipos de veículos;
- Indicadores de segurança viária.

A organização dos dados permite gerar informações para análise nacional e estadual e apoiar a identificação de regiões e situações que necessitam de maior atenção.

---

# Tecnologias Utilizadas

- Google Colab
- Python
- R
- GitHub
- Microsoft Office 365
- Microsoft Power BI
- Canva

---

# Product Backlog

| Rank | Prioridade | User Story | Estimativa (Story Points) | Sprint | Status | Requisito do Parceiro |
|---:|---|---|---:|---:|---|---|
| 1 | Alta | Visualização Nacional – Como pesquisador de segurança viária, quero visualizar dados nacionais de frota, população, mortes e sinistros em gráficos e mapas, para identificar tendências gerais. | 8 | 1 | Concluído | RN.P.1, RN.P.3 |
| 2 | Alta | Visualização Estadual – Como gestor estadual de trânsito, quero acessar métricas específicas do meu estado, para comparar indicadores locais com a média nacional. | 5 | 1 | Concluído | RN.P.3 |
| 3 | Alta | Indicadores-Chave – Como analista de dados, quero calcular mortalidade por 100 mil habitantes e sinistros por 10 mil veículos. | 8 | 1 | Concluído | RN.P.1, RN.P.2 |
| 4 | Alta | Filtros Interativos – Como usuário da plataforma, quero aplicar filtros por tipo de veículo, região, ano e gravidade do sinistro. | 13 | 2 | Não iniciado | RN.P.3, RN.P.5 |
| 5 | Média | Filtro Cruzado Saúde/Transporte – Como pesquisador acadêmico, quero cruzar dados de saúde (DATASUS) com dados de transporte (PRF). | 20 | 2 | Não iniciado | RN.P.1, RN.P.2 |
| 6 | Média | Análise de Padrões de Descanso – Como especialista em logística, quero visualizar a distância entre pontos de parada de descanso e locais de sinistros, para identificar riscos relacionados à fadiga. | 13 | 2 | Não iniciado | RN.P.2 |
| 7 | Média | Evolução Temporal – Como formulador de políticas públicas, quero analisar a evolução dos indicadores de segurança viária entre 2015 e 2025. | 8 | 3 | Não iniciado | RN.P.1, RN.P.3 |
| 8 | Baixa | Interface Intuitiva – Como usuário final, quero acessar informações com poucos cliques, para facilitar a navegação e reduzir o tempo de análise. | 5 | 3 | Não iniciado | RN.P.5 |
| 9 | Baixa | Responsividade – Como gestor em campo, quero acessar o dashboard em dispositivos móveis, para consultar os indicadores de forma prática. | 8 | 3 | Não iniciado | RN.P.6 |
| 10 | Baixa | Documentação Técnica – Como desenvolvedor, quero ter scripts de limpeza e modelagem documentados em Python, para garantir reprodutibilidade e transparência. | 3 | 3 | Não iniciado | RN.P.2, RN.P.4 |

---

# Entregas da Sprint 1

Durante a Sprint 1 foram realizadas as principais atividades relacionadas à preparação dos dados e à primeira versão da solução.

| Atividade | Status |
|---|---|
| Tratamento das bases PRF/DATATRAN | Concluído |
| Organização dos dados de 2015 a 2025 | Concluído |
| Padronização dos registros de acidentes | Concluído |
| Classificação dos tipos de veículos | Concluído |
| Preparação da base de veículos pesados | Concluído |
| Tratamento dos dados do DATASUS | Concluído |
| Tratamento dos dados populacionais do IBGE | Concluído |
| Tratamento dos dados de frota do SENATRAN | Concluído |
| Integração das bases por UF e ano | Concluído |
| Criação dos indicadores principais | Concluído |
| Validação das bases | Concluído |
| Preparação da base consolidada para o Power BI | Concluído |
| Desenvolvimento da primeira versão do dashboard | Concluído |

---

# Registro das Sprints

| Sprint | Previsão | Status | Principais Entregas |
|---|---|---|---|
| Sprint 01 | 01/10/2026 | Concluída / Em finalização | Tratamento das bases PRF, DATASUS, IBGE e SENATRAN; integração; indicadores; validação; primeira versão do Power BI |
| Sprint 02 | 29/10/2026 | Não iniciado | Filtros interativos, cruzamento PRF × DATASUS e análises adicionais |
| Sprint 03 | 26/11/2026 | Não iniciado | Evolução temporal aprofundada, interface, responsividade e documentação final |
| Feira de Soluções | 03/12/2026 | Não iniciado | Apresentação final do projeto |

---

# Situação Atual

## Sprint 1

A Sprint 1 encontra-se **concluída / em finalização**, com a base de dados preparada para análise e a primeira versão do dashboard desenvolvida.

As principais fontes utilizadas foram:

- PRF / DATATRAN;
- DATASUS;
- IBGE;
- SENATRAN.

A integração das bases foi estruturada principalmente por:

**UF + ano**

resultando em uma matriz de:

**27 UFs × 11 anos = 297 registros**

A primeira versão do Power BI permite visualizar indicadores relacionados a acidentes, mortes, população e frota.

As funcionalidades planejadas para as próximas Sprints incluem:

- Filtros interativos;
- Cruzamentos adicionais entre PRF e DATASUS;
- Análises específicas por tipo de veículo;
- Aprofundamento da análise de veículos pesados;
- Análise de padrões relacionados aos pontos de descanso;
- Melhorias de interface;
- Responsividade;
- Documentação técnica final.
