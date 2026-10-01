# 5W2H — Pathlog

| Nº | O quê (What) | Por quê (Why) | Onde (Where) | Quando (When) | Quem (Who) | Como (How) | Quanto (How Much) | User Story | Status |
|----|--------------|---------------|--------------|---------------|------------|------------|-------------------|------------|--------|
| 1 | Levantar requisitos do projeto | Definir o que o sistema precisa entregar | GitHub / reuniões | Sprint 1 | Gustavo De Oliveira | Analisando proposta, requisitos e necessidades do cliente | 4h | US 1–10 | Concluído |
| 2 | Levantar fontes de dados | Identificar fontes oficiais para o projeto | Internet / órgãos oficiais | Sprint 1 | Gustavo Nilfran | Pesquisa e seleção de PRF, DATASUS, IBGE e SENATRAN | 3h | US 3 | Concluído |
| 3 | Baixar bases PRF/DATATRAN | Obter os dados de acidentes rodoviários | Google Drive / Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Download das bases anuais de 2015 a 2025 | 2h | US 1, US 3 | Concluído |
| 4 | Organizar arquivos PRF | Facilitar o processamento das bases | Google Drive | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Separação e padronização dos arquivos por ano | 2h | US 1, US 3 | Concluído |
| 5 | Padronizar arquivos PRF | Garantir estrutura compatível entre os anos | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Tratamento de cabeçalhos, encoding, colunas e formatos | 6h | US 3 | Concluído |
| 6 | Consolidar dados PRF | Criar uma única base de acidentes | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | União das bases de 2015–2025 | 5h | US 1, US 3 | Concluído |
| 7 | Validar registros PRF | Garantir integridade dos dados | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Verificação de linhas, colunas, nulos e duplicidades | 4h | US 3 | Concluído |
| 8 | Corrigir identificação dos acidentes | Evitar exclusão indevida de registros | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Uso da chave composta id + ano | 3h | US 3 | Concluído |
| 9 | Tratar dados ausentes e inconsistentes | Melhorar a qualidade da base | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Identificação, correção e documentação dos problemas encontrados | 6h | US 3 | Concluído |
| 10 | Classificar veículos | Separar os veículos por categoria | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Padronização dos tipos de veículos | 3h | US 1, US 3 | Concluído |
| 11 | Criar classificação de veículos pesados | Identificar veículos relevantes ao projeto | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Criação da categoria Pesado | 2h | US 1, US 3 | Concluído |
| 12 | Criar base de veículos pesados | Analisar acidentes envolvendo veículos pesados | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Filtragem e tratamento dos registros classificados | 3h | US 1, US 3 | Concluído |
| 13 | Agregar veículos pesados por UF e ano | Permitir análises estaduais e temporais | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Agrupamento por UF e ano | 2h | US 2, US 3 | Concluído |
| 14 | Tratar dados do DATASUS | Obter dados complementares de óbitos | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Limpeza e padronização da base | 5h | US 5 | Concluído |
| 15 | Organizar DATASUS por UF e ano | Permitir integração com os demais dados | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Criação da matriz 27 UFs × 11 anos | 2h | US 5 | Concluído |
| 16 | Tratar dados populacionais do IBGE | Obter população para cálculo de indicadores | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Seleção de UF, ano e população total | 2h | US 3 | Concluído |
| 17 | Organizar população por UF e ano | Padronizar os dados para integração | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Estruturação em UF × ano | 1h | US 3 | Concluído |
| 18 | Tratar dados do SENATRAN | Obter dados da frota brasileira | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Tratamento das bases anuais de frota | 4h | US 3 | Concluído |
| 19 | Organizar frota por UF e ano | Permitir indicadores relacionados à frota | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Uso do total da frota por UF e ano | 2h | US 3 | Concluído |
| 20 | Integrar PRF, DATASUS, IBGE e SENATRAN | Criar uma base única para análise | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Junção utilizando UF + ano | 5h | US 3, US 5 | Concluído |
| 21 | Criar matriz UF × ano | Padronizar a estrutura do projeto | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Garantindo 27 UFs × 11 anos | 2h | US 2, US 3 | Concluído |
| 22 | Criar indicadores de acidentes | Facilitar interpretação dos dados | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Cálculo de taxas e proporções | 3h | US 3 | Concluído |
| 23 | Criar indicadores relacionados à população | Comparar acidentes e mortes considerando população | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Cálculo por 100 mil habitantes | 2h | US 3 | Concluído |
| 24 | Criar indicadores relacionados à frota | Comparar acidentes considerando tamanho da frota | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Cálculo por 10 mil/100 mil veículos | 2h | US 3 | Concluído |
| 25 | Validar base consolidada | Garantir que os dados integrados estejam corretos | Google Colab | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Auditoria de nulos, duplicidades, negativos e quantidade de registros | 4h | US 3 | Concluído |
| 26 | Exportar bases finais | Disponibilizar arquivos tratados para utilização | Google Drive | Sprint 1 | Gustavo De Oliveira, Arthur Medeiros | Exportação em CSV | 1h | US 1–3 | Concluído |
| 27 | Preparar base para Power BI | Disponibilizar dados em formato adequado para análise | Power BI | Sprint 1 | Pedro Henrique, Arthur Medeiros | Importação da base consolidada e configuração dos campos | 3h | US 1, US 3 | Concluído |
| 28 | Criar indicadores e gráficos iniciais | Construir o primeiro painel analítico | Power BI | Sprint 1 | Pedro Henrique, Arthur Medeiros | Criação de medidas, cartões, gráficos e tabelas | 6h | US 1, US 2, US 3 | Concluído |
| 29 | Criar visualização nacional | Permitir análise geral do Brasil | Power BI | Sprint 1 | Pedro Henrique, Arthur Medeiros | Cartões e gráficos com indicadores nacionais | 4h | US 1 | Concluído |
| 30 | Criar visualização estadual | Permitir comparação entre UFs | Power BI | Sprint 1 | Pedro Henrique, Arthur Medeiros | Gráficos e tabelas por estado | 4h | US 2 | Concluído |
| 31 | Criar filtros interativos | Permitir exploração personalizada dos dados | Power BI | Sprint 2 | Pedro Henrique, Arthur Medeiros | Segmentadores de ano, UF e região | 3h | US 4 | Não iniciado |
| 32 | Criar filtro por tipo de veículo | Permitir análise específica dos veículos | Power BI | Sprint 2 | Pedro Henrique, Arthur Medeiros | Segmentação por categoria de veículo | 2h | US 4 | Não iniciado |
| 33 | Criar filtro por gravidade | Permitir análise da severidade dos acidentes | Power BI | Sprint 2 | Pedro Henrique, Arthur Medeiros | Filtros por mortos, feridos e ilesos | 2h | US 4 | Não iniciado |
| 34 | Cruzar PRF e DATASUS | Comparar diferentes fontes de óbitos | Power BI | Sprint 2 | Pedro Henrique, Arthur Medeiros | Utilização dos indicadores integrados | 4h | US 5 | Não iniciado |
| 35 | Analisar padrões de localização | Identificar padrões relacionados ao local dos acidentes | Power BI | Sprint 2 | Pedro Henrique, Arthur Medeiros | Cruzamento de UF, município, rodovia e localização | 5h | US 6 | Não iniciado |
| 36 | Analisar pontos e condições de descanso | Investigar relação entre descanso e acidentes | Power BI / dados disponíveis | Sprint 2 | Pedro Henrique, Arthur Medeiros | Cruzamento das informações disponíveis sobre localização e condições | 4h | US 6 | Não iniciado |
| 37 | Aprofundar análise temporal | Identificar mudanças ao longo dos anos | Power BI | Sprint 3 | Pedro Henrique, Arthur Medeiros | Comparação anual e evolução dos indicadores | 4h | US 7 | Não iniciado |
| 38 | Criar indicadores de evolução anual | Facilitar comparação entre períodos | Power BI | Sprint 3 | Pedro Henrique, Arthur Medeiros | Cálculo de variações e tendências | 3h | US 7 | Não iniciado |
| 39 | Refinar interface do dashboard | Melhorar organização e leitura das informações | Power BI / Canva | Sprint 3 | Pedro Henrique, Arthur Medeiros | Ajustes de layout, títulos, filtros e elementos visuais | 5h | US 8 | Não iniciado |
| 40 | Criar navegação entre páginas | Facilitar utilização do dashboard | Power BI | Sprint 3 | Pedro Henrique, Arthur Medeiros | Botões, páginas e navegação interna | 3h | US 8 | Não iniciado |
| 41 | Adaptar dashboard para diferentes telas | Melhorar acessibilidade do sistema | Power BI | Sprint 3 | Pedro Henrique, Arthur Medeiros | Ajustes para diferentes resoluções e dispositivos | 3h | US 9 | Não iniciado |
| 42 | Revisar indicadores e visualizações | Corrigir problemas antes da entrega final | Power BI | Sprint 3 | Pedro Henrique, Arthur Medeiros | Revisão técnica e visual de todo o dashboard | 4h | US 7–9 | Não iniciado |
| 43 | Elaborar documentação técnica | Explicar funcionamento e tratamento dos dados | GitHub | Sprint 3 | Gustavo De Oliveira | Documentação das fontes, processos, bases e indicadores | 6h | US 10 | Não iniciado |
| 44 | Organizar repositório GitHub | Facilitar acesso e manutenção do projeto | GitHub | Sprint 3 | Gustavo De Oliveira | Organização de pastas, arquivos e documentação | 2h | US 10 | Não iniciado |
| 45 | Preparar materiais de apresentação | Apresentar o projeto ao cliente e avaliadores | Canva / PowerPoint | Sprint 3 | Gustavo Nilfran | Criação de slides, demonstrações e materiais de apoio | 5h | US 8, US 10 | Não iniciado |
| 46 | Realizar validação final do MVP | Garantir que o produto atende aos requisitos | GitHub / Power BI | Sprint 3 | Gustavo De Oliveira | Testes finais das bases, indicadores e dashboard | 5h | US 1–10 | Não iniciado |
| 47 | Preparar versão final do projeto | Consolidar todos os resultados para entrega | GitHub / Power BI | Sprint 3 | Gustavo De Oliveira | Revisão, organização e publicação da versão final | 4h | US 1–10 | Não iniciado |
| 48 | Estruturar o relatório do projeto | Organizar a narrativa completa do que foi feito | GitHub / Docs | Sprint 3 | Gustavo De Oliveira | Definição de seções: problema, objetivos, metodologia, dados, resultados e conclusões | 3h | US 11 | Não iniciado |
| 49 | Redigir seção de entendimento do problema | Documentar o problema do cliente e o contexto | GitHub / Docs | Sprint 3 | Gustavo De Oliveira | Descrição do problema de acidentes com veículos pesados, impacto e necessidade do dashboard | 3h | US 11 | Não iniciado |
| 50 | Redigir seção de metodologia e fontes | Explicar como os dados foram obtidos e tratados | GitHub / Docs | Sprint 3 | Gustavo De Oliveira | Documentação de PRF, DATASUS, IBGE, SENATRAN e do pipeline de tratamento | 4h | US 11 | Não iniciado |
| 51 | Redigir seção de resultados e indicadores | Apresentar os principais achados do projeto | GitHub / Docs | Sprint 3 | Gustavo De Oliveira | Descrição dos indicadores, visualizações e insights gerados no Power BI | 4h | US 11 | Não iniciado |
| 52 | Redigir conclusões e próximos passos | Fechar o relatório com aprendizados e recomendações | GitHub / Docs | Sprint 3 | Gustavo De Oliveira | Síntese dos resultados, limitações e sugestões de evolução | 2h | US 11 | Não iniciado |
| 53 | Revisar e formatar o relatório final | Garantir qualidade textual e visual do documento | GitHub / Docs | Sprint 3 | Gustavo De Oliveira | Revisão ortográfica, formatação, figuras e versionamento no repositório | 3h | US 11 | Não iniciado |
| 54 | Definir objetivo e público do vídeo de entendimento | Alinhar o propósito do vídeo com a comunicação do problema | Reuniões / Docs | Sprint 2 | Gustavo Nilfran | Definição de mensagem central, duração alvo e público (cliente/avaliadores) | 1h | US 12 | Não iniciado |
| 55 | Elaborar roteiro do vídeo de entendimento | Organizar a narrativa do problema do cliente | Docs / Canva | Sprint 2 | Gustavo Nilfran | Roteiro com introdução, contexto do problema, impacto, necessidade da solução e fechamento | 3h | US 12 | Não iniciado |
| 56 | Selecionar referências e materiais de apoio | Embasar o vídeo com dados e exemplos reais | Internet / bases | Sprint 2 | Gustavo Nilfran | Seleção de estatísticas, prints do dashboard e trechos relevantes do problema | 2h | US 12 | Não iniciado |
| 57 | Gravar narração e/ou takes do vídeo de entendimento | Capturar o conteúdo falado e visual | Gravação (celular/PC) | Sprint 2 | Gustavo Nilfran | Gravação da narração, tela e eventuais intervenções da equipe | 3h | US 12 | Não iniciado |
| 58 | Editar o vídeo de entendimento do problema | Montar o vídeo com ritmo, cortes e elementos visuais | Editor de vídeo | Sprint 2 | Gustavo Nilfran | Edição: cortes, legendas, transições, inserção de gráficos e ajuste de áudio | 5h | US 12 | Não iniciado |
| 59 | Revisar e exportar o vídeo de entendimento | Garantir qualidade final e formato adequado | Editor de vídeo / Drive | Sprint 2 | Gustavo Nilfran | Revisão de áudio/imagem, exportação e upload no Drive/repositório | 2h | US 12 | Não iniciado |
| 60 | Definir estrutura do vídeo final de apresentação | Organizar o fluxo completo da apresentação do projeto | Reuniões / Docs | Sprint 3 | Gustavo Nilfran | Estrutura: problema → solução → dados → dashboard → resultados → conclusões | 2h | US 13 | Não iniciado |
| 61 | Elaborar roteiro do vídeo final | Detalhar falas, tempos e transições da apresentação | Docs / Canva | Sprint 3 | Gustavo Nilfran | Roteiro completo com falas, cues de tela (dashboard) e divisão de papéis da equipe | 4h | US 13 | Não iniciado |
| 62 | Preparar demonstração do dashboard para o vídeo | Garantir que a navegação no Power BI fique clara no vídeo | Power BI | Sprint 3 | Pedro Henrique, Arthur Medeiros | Ensaio de filtros, páginas e insights a serem mostrados na gravação | 3h | US 13 | Não iniciado |
| 63 | Gravar o vídeo final de apresentação | Capturar a apresentação completa do projeto | Gravação (celular/PC) | Sprint 3 | Gustavo Nilfran | Gravação da apresentação com narrativa, tela do dashboard e participação da equipe | 4h | US 13 | Não iniciado |
| 64 | Editar o vídeo final de apresentação | Produzir a versão final polida do vídeo | Editor de vídeo | Sprint 3 | Gustavo Nilfran | Edição completa: cortes, legendas, inserções de gráficos, trilha e ajustes de áudio/imagem | 6h | US 13 | Não iniciado |
| 65 | Revisar, exportar e publicar o vídeo final | Entregar o vídeo no formato e canal adequados | Editor de vídeo / Drive / GitHub | Sprint 3 | Gustavo Nilfran | Revisão final, exportação em alta qualidade e disponibilização no Drive/repositório | 2h | US 13 | Não iniciado |

---

## Resumo por Sprint

| Sprint | Atividades | Qtd. | Horas | Situação |
|--------|------------|------|-------|----------|
| Sprint 1 | 1–30 | 30 | 97h | Concluído |
| Sprint 2 | 31–36, 54–59 | 12 | 36h | Não iniciado |
| Sprint 3 | 37–53, 60–65 | 23 | 84h | Não iniciado |
| **TOTAL** | **1–65** | **65** | **217h** | — |

---

## User Stories

| US | Descrição | Atividades | Horas (aprox.) | Status |
|----|-----------|------------|----------------|--------|
| US 1 | Visualização nacional / base | 1, 3, 4, 6, 10–12, 26–29, 46, 47 | 45h | Concluído (parcial) |
| US 2 | Visualização estadual | 13, 21, 28, 30 | 14h | Concluído (parcial) |
| US 3 | Núcleo de dados e indicadores | 2–13, 16–28 | 70h | Concluído |
| US 4 | Filtros interativos | 31–33 | 7h | Não iniciado |
| US 5 | Cruzamento PRF × DATASUS | 14, 15, 20, 34 | 16h | Parcial |
| US 6 | Padrões de localização / descanso | 35, 36 | 9h | Não iniciado |
| US 7 | Análise temporal | 37, 38, 42 | 11h | Não iniciado |
| US 8 | Interface e navegação | 39, 40, 45 | 13h | Não iniciado |
| US 9 | Responsividade | 41, 42 | 7h | Não iniciado |
| US 10 | Documentação e entrega | 43–47 | 22h | Não iniciado |
| US 11 | Relatório completo do projeto | 48–53 | 19h | Não iniciado |
| US 12 | Vídeo de entendimento do problema | 54–59 | 16h | Não iniciado |
| US 13 | Vídeo final de apresentação | 60–65 | 21h | Não iniciado |
