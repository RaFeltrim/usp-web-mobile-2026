# SSC0961 — Desenvolvimento Web e Mobile

[![ICMC - USP](https://img.shields.io/badge/USP-ICMC-blue.svg)](https://www.icmc.usp.br/)
[![Department](https://img.shields.io/badge/Departamento-SSC-informational.svg)](https://www.icmc.usp.br/departamentos/ssc)
[![Course](https://img.shields.io/badge/Disciplina-SSC0961-brightgreen.svg)](https://edisciplinas.usp.br)
[![Status](https://img.shields.io/badge/Status-Concluído%20%2F%20Aprovado-success.svg)]()
[![GitHub Repo](https://img.shields.io/badge/GitHub-usp--web--mobile--2026-181717?style=flat-square&logo=github)](https://github.com/RaFeltrim/usp-web-mobile-2026)
[![SIBiSC Hub](https://img.shields.io/badge/Projeto-SIBiSC--Hub--Cultural-orange?style=flat-square&logo=react)](https://github.com/RaFeltrim/sibisc-hub-cultural)
[![Portfolio Profissional](https://img.shields.io/badge/Portfólio-Profissional-purple?style=flat-square)](https://github.com/RaFeltrim/portfolio)
[![QA & IA Portfolio](https://img.shields.io/badge/QA%20%26%20IA-Portfolio-success?style=flat-square)](https://github.com/RaFeltrim/qa-ia-portfolio)
[![WCAG](https://img.shields.io/badge/WCAG-2.1%20AA-005A9C?style=flat-square)](./SIBiSC/docs/qa/relatorio_acessibilidade.md)

Repositório central de estudos, anotações, trabalhos práticos, resumos teóricos, código-fonte e materiais de apoio da disciplina **SSC0961 — Desenvolvimento Web e Mobile**, ministrada no Instituto de Ciências Matemáticas e de Computação (**ICMC - USP**).

Repositório Oficial no GitHub: **[RaFeltrim/usp-web-mobile-2026](https://github.com/RaFeltrim/usp-web-mobile-2026)** *(Seguindo o padrão arquitetural de [RaFeltrim/usp-apoo-2026](https://github.com/RaFeltrim/usp-apoo-2026))*.

---

- **Instituição:** Universidade de São Paulo (USP) — ICMC São Carlos
- **Departamento:** Departamento de Sistemas de Computação (SSC)
- **Código da Disciplina:** SSC0961
- **Semestre:** 2026.1
- **Docente Responsável:** Profa. Dra. Lina Garcés ([linagarces@usp.br](mailto:linagarces@usp.br))
  - *Gabinete:* Sala 4-107, Bloco 4 do ICMC - USP
  - *Horário de Atendimento:* Quartas-feiras, das 17h00 às 19h00
- **Horários e Locais:**
  - **Aulas Teóricas e Práticas:** Segunda-feira às 19h00 (Sala 5-104 do ICMC)
  - **Laboratórios de Prototipação e Design:** Salas 6303, 6304 e 6305 do ICMC
- **Ambiente Virtual:** [e-Disciplinas Moodle USP (SSC0961)](https://edisciplinas.usp.br)

---

## 🌐 Ecossistema de Projetos Remotos Conectados

Como fruto dos módulos teóricos, práticos e entregas da disciplina, foram concebidos e publicados **4 projetos e repositórios independentes** no GitHub:

| Repositório Remoto | Escopo & Papel | Tecnologias Chave |
| :--- | :--- | :--- |
| 🏛️ **[RaFeltrim/sibisc-hub-cultural](https://github.com/RaFeltrim/sibisc-hub-cultural)** | **Projeto Oficial em Grupo da Disciplina:** Web-app mobile-first para o Sistema Integrado de Bibliotecas Públicas de São Carlos. | React 19, Vite 6, Supabase PostgreSQL, RLS, Playwright E2E, WCAG 2.1 AA |
| 💼 **[RaFeltrim/portfolio](https://github.com/RaFeltrim/portfolio)** | **Portfólio Profissional Completo:** Portal institucional de carreira, engenharia de software e arquitetura web. | HTML5, CSS Moderno, Liquid Glass, CI/CD GitHub Actions |
| 🧪 **[RaFeltrim/qa-ia-portfolio](https://github.com/RaFeltrim/qa-ia-portfolio)** | **Portfólio Especializado em QA & IA:** Demonstração avançada de testes E2E, Shift-Left, contratos e agentes de validação. | Playwright, Vitest, Cypress, Robot Framework, Mock Service Worker |
| 🎓 **[RaFeltrim/portfolio-academico-web-mobile](https://github.com/RaFeltrim/portfolio-academico-web-mobile)** | **Portfólio Acadêmico da Disciplina:** Aplicação web estática e responsiva desenvolvida como requisito prático da Atividade 9. | HTML5 semântico, CSS Grid/Flexbox, GitHub Pages |

---

```text
usp-web-mobile-2026/
│
├── 📁 Tópico 0 - Informacoes Gerais/
│   ├── README.md                                                 # Apresentação docente, horários, plano e regras da disciplina
│   └── 📁 Material de Apoio/
│       ├── 2026_Cronograma da disciplina SSC0961 - Desenvolvimento web e mobile.docx.pdf # Cronograma oficial e critérios
│       ├── 2026_Descrição do projeto SSC0961 - Desenvolvimento web e mobile.docx.pdf     # Diretrizes das entregas 1 e 2
│       ├── Ementa_Oficial_JúpiterWeb_SSC0961.pdf                 # Programa e bibliografia oficial no JúpiterWeb
│       ├── Desenvolvimento_Web_e_Mobile_Usp_1_SEM2026.pdf        # Ficha discente e comprovante de matrícula ICMC-USP
│       ├── Júpiter_Web_Comprovante_Matricula.pdf                 # Comprovante de matrícula no sistema da Pró-Reitoria
│       └── Historico_Escolar_USP.pdf                             # Histórico escolar emitido pela USP
│
├── 📁 Tópico 1 - Introducao e Ecossistema Web/                   # (Semanas 1 e 2)
│   ├── README.md                                                 # Resumo: História da Web, W3C, HTTP/HTTPS e DevTools
│   ├── 📁 Material de Apoio/
│   │   ├── Aula 01 - Introdução ao Desenvolvimento Web e Mobile.pdf # Slides introdutórios da Profa. Lina Garcés
│   │   └── Aula 02 - Ecossistema de Desenvolvimento na Web.pdf   # Slides de arquitetura web, W3C e protocolos
│   └── 📁 Entregas/
│       ├── 📁 Desafio 01 - Website sobre a Web com IA/
│       │   ├── README.md                                         # Diretrizes e reflexões sobre uso de IA generativa
│       │   └── Desafio - construção de um website sobre a web com apoio de IA.docx.pdf
│       └── 📁 Atividade 02 - DevTools Inspecao/
│           ├── README.md                                         # Auditoria de rede, latência e waterfall
│           ├── devtools_inspecao_final.md                        # Relatório técnico completo
│           ├── devtools_inspecao_final.pdf                       # Relatório formal em PDF
│           └── prints/                                           # Capturas de tela e arquivo HAR
│
├── 📁 Tópico 2 - Desenvolvimento de Aplicativos Moveis/          # (Semanas 3 a 5)
│   ├── README.md                                                 # Resumo: Nativo vs Híbrido vs PWA, Frameworks e UX Mobile
│   ├── 📁 Material de Apoio/
│   │   ├── Aula 3 - Introdução ao Desenvolvimento de Aplicativos Móveis.pdf # Slides de desenvolvimento mobile
│   │   └── mobile_mockup.png                                     # Mockup de layout mobile
│   └── 📁 Entregas/
│       ├── 📁 Atividade 07 - Pagina HTML Puro (Desafio Alura)/
│       │   ├── README.md                                         # Estruturação semântica HTML5
│       │   └── index.html                                        # Código-fonte da página web
│       └── 📁 Atividade 09 - CSS e Portfolio/
│           ├── README.md                                         # Enunciado, objetivos e relatórios de estilo
│           ├── Atividade - CSS (1).docx                          # Arquivo de entrega oficial
│           ├── respostas_css.md                                  # Questionário teórico respondido
│           ├── respostas_css.pdf                                 # Versão em PDF
│           ├── AtPortifolio.jpeg                                 # Evidência de layout
│           ├── Atv2.jpeg                                         # Evidência de responsividade
│           └── 📁 portfolio_academico/                           # Código do portfólio acadêmico
│
├── 📁 Tópico 3 - Backend e Integracao com Banco de Dados/        # (Semana 10)
│   ├── README.md                                                 # Resumo: Arquitetura de Backend, REST APIs e BaaS Supabase
│   └── 📁 Material de Apoio/
│       └── backend .pdf                                          # Slides de backend (Diego Gomes de Santana)
│
├── 📁 Tópico 4 - Qualidade, Testes Automatizados e Seguranca/    # (Semanas 11, 13 e 15)
│   ├── README.md                                                 # Resumo: Testes Combinatoriais, Selenium/Playwright e OWASP
│   ├── 📁 Material de Apoio/
│   │   ├── Aula 06 - Teste Funcional Combinatorial com Selenium.pdf # Slides de teste combinatorial e Selenium
│   │   └── Sec_USP_2.pdf                                         # Palestra de Segurança Web (Dr. Misael Júnior)
│   └── 📁 Entregas/
│       └── 📁 Atividade 11 - Teste Funcional Selenium/
│           ├── README.md                                         # Tabela de testes, bugs e evidências
│           ├── desafio_teste_combinatorial_com_SELENIUM.pdf      # Enunciado oficial da professora
│           ├── relatorio_testes_selenium.md                      # Relatório técnico completo
│           ├── relatorio_testes_selenium.pdf                     # Relatório em PDF
│           ├── cadastro-usuario-testes-rafaelfeltrim.side        # Projeto executável do Selenium IDE
│           ├── Atividade-08-06.zip                               # Pacote compactado original
│           └── 📁 evidencias/                                    # 17 capturas de tela comprovando os testes
│
├── 📁 Entregas do Projeto - SIBiSC/
│   ├── 📁 01-Concepcao-e-Estudo-de-Frameworks/                   # [ENTREGA 1 - 27/04/2026]
│   │   ├── README.md                                             # Relatório síntese: Personas, Casos de Uso e Frameworks
│   │   ├── Web-App-do-SIBiSC - Entrega 01.pdf                    # Documento formal completo entregue à banca
│   │   └── _USP__Desenvolvimento_Web_e_Mobile___Entrega_01.pdf   # Versão encadernada
│   │
│   ├── 📁 02-Aplicacao-Final-Testes-e-Deploy/                    # [ENTREGA FINAL - 22 e 29/06/2026]
│   │   ├── README.md                                             # Relatório síntese: Arquitetura, Testes E2E, QA e Deploy
│   │   ├── SIBiSC-Hub-Cultural - Entrega Final.pdf               # Relatório oficial consolidado final
│   │   ├── _USP__Desenvolvimento_Web_e_Mobile___Entrega_Final.pdf# Versão encadernada da entrega final
│   │   ├── correlation_matrix_sibisc_v2.html                     # Visualização analítica interativa
│   │   └── download.htm                                          # Snapshot estático do aplicativo
│   │
│   └── 📁 Submissao-Consolidada-Prof-Lina/                       # Dossiê de Submissão Final à Profa. Dra. Lina Garcés
│       ├── 00_LEIA-ME_ENTREGA.md                                 # Guia mestre e checklist de envio
│       ├── RELATORIO_FINAL_SIBISC.md                             # Relatório acadêmico completo
│       ├── WEB_E_MOBILE_PROF_LINA_2026.zip                       # Pacote zip oficial submetido
│       ├── 📁 PDFs/ e 📁 MDs/                                    # Versões formatadas de todos os relatórios
│       └── 📁 APOIO_ENVIO_PROF_LINA_2026/                        # E-mail formal encaminhado e anexos
│
├── 📁 Projetos-Individuais/
│   └── 📁 Study-Sync/                                            # Projeto Individual: React 19 + TypeScript + Supabase + Edge Functions
│       ├── src/                                                  # Lógica da aplicação com Pomodoro e Liquid Glass
│       ├── supabase/                                             # Migrations PostgreSQL e Edge Functions Deno
│       ├── tests/                                                # Suíte de testes com Vitest e Playwright
│       └── README.md                                             # Documentação completa do Study-Sync
│
├── 📁 SIBiSC/                                                    # Código-fonte completo da aplicação do projeto
│   ├── src/                                                      # Componentes React 19, páginas, rotas, hooks e serviços
│   ├── docs/                                                     # Documentação técnica de arquitetura, QA, DevOps e produto
│   ├── docs_pdfs/                                                # PDFs renderizados da documentação técnica
│   └── package.json                                              # Dependências do frontend Vite + React
│
├── .gitignore                                                    # Filtros de dependências e artefatos de build
└── README.md                                                     # Portal central de navegação no padrão Gold
```

---

## 🗂️ Estrutura Oficial do Repositório por Módulos & Semanas

O repositório é segmentado para acompanhar o cronograma do semestre letivo de 2026 da USP:

- **Tópico 0 — Informações Gerais:** Diretrizes docentes, regras de aprovação, cronograma oficial e especificação das duas entregas do projeto.
- **Tópico 1 — Introdução e Ecossistema Web:** Fundamentos da World Wide Web, protocolos de rede (HTTP/HTTPS), depuração avançada com Chrome DevTools e primeiro desafio prático assistido por IA Generativa.
- **Tópico 2 — Desenvolvimento Mobile:** Estudo comparativo de paradigmas móveis (PWA, Frameworks nativos multiplataforma e soluções híbridas) e prototipagem no Figma.
- **Tópico 3 — Backend e Persistência:** Serviços de retaguarda, APIs RESTful, modelagem relacional PostgreSQL e políticas de segurança declarativa via Row Level Security (RLS) no Supabase.
- **Tópico 4 — Qualidade e Segurança:** Automação de testes funcionais combinatoriais, testes E2E com Playwright/Selenium, diretrizes de acessibilidade WCAG 2.1 AA e segurança de aplicações web e móveis.
- **Entregas do Projeto:** Todos os relatórios formais, apresentações, matrizes analíticas e evidências de entrega das etapas 1 e final do projeto semestral.

---

## 📚 Mapa Geral de Atividades & Entregas da Disciplina

| Atividade | Módulo / Tópico | Prazo | Status | Arquivo Final de Entrega |
| :--- | :--- | :---: | :---: | :--- |
| **Atividade 1 (História da Web com IA)** | Tópico 1 — Ecossistema Web | 02/03/2026 | ✅ **Entregue** | [`Desafio - Website com IA.docx.pdf`](./Tópico%201%20-%20Introducao%20e%20Ecossistema%20Web/Entregas/Desafio%2001%20-%20Website%20sobre%20a%20Web%20com%20IA/Desafio%20-%20construção%20de%20um%20website%20sobre%20a%20web%20com%20apoio%20de%20IA.docx.pdf) |
| **Atividade 2 (DevTools Inspeção)** | Tópico 1 — Ecossistema Web | 09/03/2026 | ✅ **Entregue** | [`devtools_inspecao_final.md`](./Tópico%201%20-%20Introducao%20e%20Ecossistema%20Web/Entregas/Atividade%2002%20-%20DevTools%20Inspecao/devtools_inspecao_final.md) |
| **Atividade 4 (Análise de Frameworks)** | Tópico 2 — Apps Móveis | 16/03/2026 | ✅ **Entregue** | [`README.md (Tópico 2)`](./Tópico%202%20-%20Desenvolvimento%20de%20Aplicativos%20Moveis/README.md) |
| **Atividades 5 & 6 (Prototipação Figma)** | Tópico 2 — Apps Móveis | 23/03/2026 | ✅ **Entregue** | [`FIGMA_SCREENS_SPEC.md`](./SIBiSC/docs/FIGMA_SCREENS_SPEC.md) |
| **Atividade 7 (Página HTML Puro)** | Tópico 2 — Apps Móveis | 06/04/2026 | ✅ **Entregue** | [`index.html (Desafio Alura)`](./Tópico%202%20-%20Desenvolvimento%20de%20Aplicativos%20Moveis/Entregas/Atividade%2007%20-%20Pagina%20HTML%20Puro%20(Desafio%20Alura)/index.html) |
| **Atividade 9 (Estilos & Portfólio CSS)** | Tópico 2 — Apps Móveis | 13/04/2026 | ✅ **Entregue** | [`Atividade - CSS (1).docx`](./Tópico%202%20-%20Desenvolvimento%20de%20Aplicativos%20Moveis/Entregas/Atividade%2009%20-%20CSS%20e%20Portfolio/Atividade%20-%20CSS%20(1).docx) |
| **PROJETO — ENTREGA 1 (Concepção)** | Entregas do Projeto | 27/04/2026 | ✅ **Entregue** | [`Web-App-do-SIBiSC - Entrega 01.pdf`](./Entregas%20do%20Projeto%20-%20SIBiSC/01-Concepcao-e-Estudo-de-Frameworks/Web-App-do-SIBiSC%20-%20Entrega%2001.pdf) |
| **Atividade 10 (Backend & Banco de Dados)** | Tópico 3 — Backend & BD | 04/05/2026 | ✅ **Entregue** | [`docs/data/modelo_de_dados.md`](./SIBiSC/docs/data/modelo_de_dados.md) |
| **Atividade 11 (Teste Funcional Selenium)** | Tópico 4 — Qualidade & QA | 11/05/2026 | ✅ **Entregue** | [`relatorio_testes_selenium.md`](./Tópico%204%20-%20Qualidade,%20Testes%20Automatizados%20e%20Seguranca/Entregas/Atividade%2011%20-%20Teste%20Funcional%20Selenium/relatorio_testes_selenium.md) |
| **Atividade 12 (Testes de Segurança)** | Tópico 4 — Qualidade & QA | 25/05/2026 | ✅ **Entregue** | [`casos_de_teste_seguranca.md`](./SIBiSC/docs/qa/casos_de_teste_seguranca.md) |
| **Atividade 13 (Acessibilidade Automatizada)** | Tópico 4 — Qualidade & QA | 08/06/2026 | ✅ **Entregue** | [`relatorio_acessibilidade.md`](./SIBiSC/docs/qa/relatorio_acessibilidade.md) |
| **PROJETO — ENTREGA FINAL (Completo)** | Entregas do Projeto | 22/06/2026 | ✅ **Entregue** | [`SIBiSC-Hub-Cultural - Entrega Final.pdf`](./Entregas%20do%20Projeto%20-%20SIBiSC/02-Aplicacao-Final-Testes-e-Deploy/SIBiSC-Hub-Cultural%20-%20Entrega%20Final.pdf) |
| **SUBMISSÃO CONSOLIDADA (Prof. Lina)** | Entregas do Projeto | 29/06/2026 | ✅ **Aprovado** | [`Submissao-Consolidada-Prof-Lina`](./Entregas%20do%20Projeto%20-%20SIBiSC/Submissao-Consolidada-Prof-Lina/README.md) |

---

## 📱 Projeto Prático da Disciplina — SIBiSC (Hub Cultural Digital)

O **SIBiSC (Sistema Integrado de Bibliotecas de São Carlos)** é um web-app mobile-first concebido para unificar o acesso aos serviços culturais do município:

| Pilar | Funcionalidade | Implementação |
|---|---|---|
| 📰 **Notícias** | Feed atualizado de comunicados e eventos das bibliotecas | Feed reativo com paginação e ordenação temporal |
| 📅 **Eventos** | Agenda cultural com filtros por unidade e faixa etária | Sistema de inscrição e filtros por taxonomia |
| 📚 **Catálogo** | Busca de acervo com disponibilidade e geolocalização | Busca com debounce, georreferenciamento e mapa |

### Stack Tecnológica
- **Frontend:** React 19, Vite 6, CSS Modules, Lucide React
- **Backend / Persistência:** Supabase (PostgreSQL, Row Level Security, Auth, Edge Functions)
- **Qualidade & Automação:** Playwright E2E, axe-core (WCAG 2.1 AA), CI/CD via GitHub Actions
- **Mobilidade:** Capacitor & Progressive Web App (PWA)

---

## 👥 Equipe e Autoria

**Desenvolvido pelo Grupo no ICMC - Universidade de São Paulo (USP):**

| Integrante | Nº USP | Papel Principal no Projeto |
| :--- | :---: | :--- |
| **Rafael Feltrim** ([GitHub](https://github.com/RaFeltrim)) | 15942812 | Lead Developer, QA & Engenharia de Software |
| **Eduardo Paz e Silva** | 15506648 | Desenvolvedor Fullstack |
| **Matheus Marchi Baron** | 15478426 | Desenvolvedor Fullstack |
| **Pedro Augusto Pereira Magalhães** | 15485458 | Desenvolvedor Fullstack |
| **Pedro Dorigatti Aureo Ferreira** | 15579930 | Desenvolvedor Fullstack |