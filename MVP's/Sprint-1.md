# 📌 MVP - [Pathlog]

## 🎯 Objetivo do MVP

Descrever de forma clara qual é o propósito do MVP:

**Qual problema resolve?**  
Existem muitos dados sobre acidentes envolvendo veículos pesados, mas essas informações estão espalhadas em diferentes fontes oficiais (PRF, DATASUS, IBGE e SENATRAN) e são difíceis de analisar em conjunto, pois não passam por tratamento, padronização e integração.

**Qual hipótese será validada?**  
Se os dados de sinistralidade forem coletados, organizados, tratados e apresentados em uma ferramenta de Business Intelligence, então será possível identificar regiões de maior risco e apoiar decisões para melhorar a segurança nas estradas com foco em veículos pesados.

**Qual valor será entregue ao usuário final?**  
Uma ferramenta que transforma dados dispersos e difíceis de interpretar em informações visuais e fáceis de entender, permitindo ao ONSV (Observatório Nacional de Segurança Viária) identificar regiões de maior risco e apoiar decisões de segurança viária com foco em veículos pesados.

---

## 📝 Descrição da Solução

Breve explicação do que será desenvolvido e entregue nesta etapa.

Nesta primeira versão (Sprint 1), a ferramenta permite analisar os indicadores de sinistralidade no trânsito com foco em veículos pesados, apresentando métricas nacionais e por estado, como mortalidade, severidade dos sinistros, frota e população.

Foi construída uma base consolidada a partir de quatro fontes oficiais:
- **PRF/DATATRAN** (acidentes rodoviários 2015–2025)
- **DATASUS** (óbitos)
- **IBGE** (população)
- **SENATRAN** (frota veicular)

Os dados foram padronizados, validados, integrados pela chave UF × ano (matriz 27 UFs × 11 anos) e utilizados para o cálculo de indicadores (incluindo taxas por 100 mil habitantes e por 10 mil/100 mil veículos). O resultado foi disponibilizado em um dashboard Power BI com visualização nacional e estadual.

**Limitações conhecidas:** nesta primeira versão (Sprint 1), a ferramenta ainda não conta com os filtros interativos por tipo de veículo, região, ano e gravidade do sinistro (previstos para a Sprint 2), nem com o cruzamento visual de dados de saúde (DATASUS) e transporte (PRF) no dashboard (previsto para as Sprints 2 e 3). A evolução temporal refinada dos indicadores, a análise de pontos de descanso, a interface polida, a responsividade e os entregáveis de documentação/vídeos também ficam para as Sprints 2 e 3.

**Escopo reduzido:** (somente o essencial para validar a ideia) a Sprint 1 concentra-se nas três user stories de prioridade Alta — Visualização Nacional, Visualização Estadual e Base consolidada com Indicadores-Chave (mortalidade por 100 mil habitantes e sinistros por 10 mil/100 mil veículos) — que formam a base de dados e visualização sobre a qual os filtros e cruzamentos das próximas sprints serão construídos.

---

## 👥 Personas / Usuários-Alvo

O analista do ONSV (Observatório Nacional de Segurança Viária) necessita de uma ferramenta que colete, organize e apresente os dados de sinistralidade no trânsito envolvendo veículos pesados, para identificar regiões de maior risco e apoiar decisões que melhorem a segurança nas estradas.

---

## 🔑 User Stories (Backlog do MVP)

| Rank | Prioridade | User Story | Estimativa | Sprint | Requisito do Parceiro |
|------|------------|------------|------------|--------|-----------------------|
| 1 | Alta | Como pesquisador de segurança viária, quero visualizar dados nacionais de frota, população, mortes e sinistros em gráficos e mapas, para identificar tendências gerais | 8 | 1 | RN.P.1, RN.P.3 |
| 2 | Alta | Como gestor estadual de trânsito, quero acessar métricas específicas do meu estado, para comparar indicadores locais com a média nacional | 5 | 1 | RN.P.3 |
| 3 | Alta | Como analista de dados, quero calcular mortalidade por 100 mil habitantes e sinistros por 10 mil veículos a partir de uma base consolidada e confiável | 8 | 1 | RN.P.1, RN.P.2 |

---

## 📅 Sprint(s) Relacionadas

| Sprint | Entregas Principais | Status |
|--------|---------------------|--------|
| 01 | Visualização Nacional, Visualização Estadual, Base consolidada e Indicadores-Chave | Concluído |
| 02 | Filtros interativos, cruzamento PRF × DATASUS (parte 1), vídeo de entendimento do problema | Não iniciado |
| 03 | Análise temporal, interface/navegação, responsividade, relatório, vídeo final, documentação e entrega | Não iniciado |

---

## 📊 Critérios de Aceitação

- [x] A ferramenta deve permitir que o usuário visualize dados nacionais e estaduais de frota, população, mortes e sinistros em gráficos e cartões.
- [x] O sistema deve calcular corretamente os indicadores de mortalidade por 100 mil habitantes e sinistros por 10 mil/100 mil veículos, a partir dos dados de frota, população e sinistros.
- [x] O usuário deve conseguir comparar os indicadores do seu estado com a média nacional.
- [x] As bases PRF, DATASUS, IBGE e SENATRAN devem estar tratadas, integradas (UF × ano) e exportadas.
- [x] A base consolidada deve estar importada e configurada no Power BI.

**Métricas coletadas:** precisão dos indicadores calculados, integridade da base consolidada (nulos, duplicidades, quantidade de registros) e correta atualização da visualização ao analisar dados nacionais e por estado.

---

## 📈 Métricas de Avaliação

| Backlog de Produto | Backlog de Sprint | Alocação de Tarefas | Documentação no GitHub | Review - Apresentação | Conformidade Técnica | PACER | Total |
|--------------------|-------------------|---------------------|------------------------|-----------------------|----------------------|-------|-------|
| 10% | 10% | 10% | 10% | 10% | 10% | 30% | 90%* |
| — | — | — | — | — | — | — | — |

\* Os 90% acima vêm do Quadro Geral de Avaliação. Os 10% restantes da nota final são avaliados individualmente, ao final do semestre, com base em "O que aprendi?" e "O que desenvolvi?" — não fazem parte desta tabela.

---

## 🚀 Próximos Passos

- Implementar os filtros interativos por tipo de veículo, região, ano e gravidade do sinistro (Sprint 2 — US 4);
- Implementar o cruzamento de dados de saúde (DATASUS) com dados de transporte (PRF) no dashboard (Sprints 2 e 3 — US 5);
- Produzir o vídeo de entendimento do problema do cliente (Sprint 2 — US 12);
- Aprofundar a análise temporal dos indicadores (2015–2025) (Sprint 3 — US 7);
- Refinar interface, navegação e responsividade do dashboard (Sprint 3 — US 8 e US 9);
- Elaborar o relatório completo do projeto e o vídeo final de apresentação (Sprint 3 — US 11 e US 13);
- Finalizar documentação técnica, repositório GitHub e versão final do MVP (Sprint 3 — US 10).

---

## 📂 Anexos / Evidências

- **Base de dados:** PRF/DATATRAN (2015–2025), DATASUS, IBGE, SENATRAN — tratadas e consolidadas (CSV no Google Drive)
- **Interface do dashboard:** Power BI — visualização nacional e estadual
- **Apresentação (slides):** [a preencher]
- **5W2H:** [disponível]
- **Repositório GitHub:**
