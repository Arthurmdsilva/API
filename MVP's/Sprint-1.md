# 📌 MVP - [Pathlog]

## 🎯 Objetivo do MVP
> Descrever de forma clara qual é o propósito do MVP:  
- Qual problema resolve? Existem muitos dados sobre acidentes envolvendo veículos pesados, mas essas informações estão espalhadas e são difíceis de analisar em conjunto, já que não passam por tratamento de dados.

- Qual hipótese será validada? Se os dados de sinistralidade forem coletados, organizados e apresentados em uma ferramenta de Business Intelligence, então será possível identificar regiões de maior risco e apoiar decisões para melhorar a segurança nas estradas.

- Qual valor será entregue ao usuário final? Uma ferramenta que transforma dados dispersos e difíceis de interpretar em informações visuais e fáceis de entender, permitindo ao ONSV (Observatório Nacional de Segurança Viária) identificar regiões de maior risco e apoiar decisões de segurança viária com foco em veículos pesados.

---

## 📝 Descrição da Solução
> Breve explicação do que será desenvolvido e entregue nesta etapa.  
- Dentre as principais funcionalidades incluídas, a ferramenta permite analisar os indicadores de sinistralidade no trânsito com foco em veículos pesados, apresentando métricas por estado e nacionalmente, como mortalidade, severidade dos sinistros, frota, população e uso de motocicletas, entre outros.
- O projeto também apresenta uma análise dos pontos de parada de descanso e a distância entre esses pontos e a localização dos sinistros envolvendo veículos pesados, para apoiar a identificação de riscos relacionados à fadiga.
- Limitações conhecidas: nesta primeira versão (Sprint 1), a ferramenta ainda não conta com os filtros interativos por tipo de veículo, região, ano e gravidade do sinistro (previstos para a Sprint 2), nem com o cruzamento de dados de saúde (DATASUS) e transporte (PRF) (previsto para as Sprints 2 e 3). A evolução temporal dos indicadores (2015–2025) e a responsividade para dispositivos móveis também ainda não estão no backlog priorizado até a Sprint 3.

- Escopo reduzido: (somente o essencial para validar a ideia) a Sprint 1 concentra-se nas três user stories de prioridade Alta — Visualização Nacional, Visualização Estadual e Indicadores-Chave (mortalidade por 100 mil habitantes e sinistros por 10 mil veículos) — que formam a base de dados e visualização sobre a qual os filtros e cruzamentos de dados das próximas sprints serão construídos.
---

## 👥 Personas / Usuários-Alvo

- O analista do ONSV (Observatório Nacional de Segurança Viária) necessita de uma ferramenta que colete, organize e apresente os dados de sinistralidade no trânsito envolvendo veículos pesados, para identificar regiões de maior risco e apoiar decisões que melhorem a segurança nas estradas.

---

## 🔑 User Stories (Backlog do MVP)
| Rank | Prioridade | User Story                                                                                                                                                                                                        | Estimativa | Sprint | Requisito do Parceiro |
|------|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|------------|--------|--------|
| 1    | Alta       | Como pesquisador de segurança viária, quero visualizar dados nacionais de frota, população, mortes e sinistros em gráficos e mapas, para identificar tendências gerais | 8 | 1 | RN.P.1, RN.P.3
| 2    | Alta       | Como gestor estadual de trânsito, quero acessar métricas específicas do meu estado, para comparar indicadores locais com a média nacional | 5 | 1 | RN.P.3
| 3    | Alta       | Como analista de dados, quero calcular mortalidade por 100 mil habitantes e sinistros por 10 mil veículos | 8 | 1 | RN.P.1, RN.P.2                                                                                   | 

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | Visualização Nacional, Visualização Estadual, Indicadores-Chave | [Em Andamento]
| 02     | Filtros Interativos, Filtro Cruzado Saúde/Transporte (parte 1).
| 03     | Filtro Cruzado Saúde/Transporte (conclusão)                     |

---

## 📊 Critérios de Aceitação
- A ferramenta deve permitir que o usuário visualize dados nacionais e estaduais de frota, população, mortes e sinistros em gráficos e mapas.
- O sistema deve calcular corretamente os indicadores de mortalidade por 100 mil habitantes e sinistros por 10 mil veículos, a partir dos dados de frota, população e sinistros.
- O usuário deve conseguir comparar os indicadores do seu estado com a média nacional.
- Métricas coletadas: precisão dos indicadores calculados, tempo de resposta dos gráficos e mapas, e correta atualização da visualização ao trocar de estado.

---

## 📈 Métricas de Avaliação
| Backlog de Produto| Backlog de Sprint	| Alocação de Tarefas	| Documentação no GitHub| 	Review - Apresentação	| Conformidade Técnica| PACER | Total |
|-------------------|-------------------|-------------------|-------------------|-------------------|-------------------|-------------------|-|
|10%|10%|10%|10%|10%|10%|30%|90%*
|_|_|_|_|_|_|_|_

\* Os 90% acima vêm do Quadro Geral de Avaliação. Os **10% restantes da nota final** são avaliados individualmente, ao final do semestre, com base em "O que aprendi?" e "O que desenvolvi?" — não fazem parte desta tabela.


---

## 🚀 Próximos Passos
- Implementar os filtros interativos por tipo de veículo, região, ano e gravidade do sinistro (Sprint 2);
- Implementar o cruzamento de dados de saúde (DATASUS) com dados de transporte (PRF) (Sprints 2 e 3);
- Avaliar a inclusão da análise de padrões de descanso (distância entre pontos de parada e locais de sinistros) e da evolução temporal dos indicadores (2015–2025), previstas no backlog completo mas ainda fora do escopo das Sprints 1 a 3.

---

## 📂 Anexos / Evidências
- Base de dados: (Datasus e PRF),(á verificar)
- Interface do dashboard: [em branco]
- Apresentação (slides): [em branco]
- 5W2H: [em branco].
