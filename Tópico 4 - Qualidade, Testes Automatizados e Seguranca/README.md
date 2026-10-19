# Tópico 4 — Qualidade, Testes Automatizados e Segurança

## 🔗 Recursos e Arquivos de Apoio
- **Slides da Aula 06 / 08:** [`Aula 06 - Teste Funcional Combinatorial com Selenium.pdf`](./Material%20de%20Apoio/Aula%2006%20-%20Teste%20Funcional%20Combinatorial%20com%20Selenium.pdf) *(Profa. Dra. Lina Garcés)*
- **Palestra de Segurança Web e Móvel:** [`Sec_USP_2.pdf`](./Material%20de%20Apoio/Sec_USP_2.pdf) *(Navegue com Segurança: Conheça as Armadilhas da Web — Dr. Misael Júnior)*

---

## 📖 Estrutura Conceitual do Módulo

### 1. Teste Funcional e Técnicas Combinatoriais
- Particionamento em classes de equivalência e análise de valor limite (BVA).
- Geração de testes combinatórios (*Pairwise/T-wise testing*) para mitigar a explosão de combinações de inputs.
- Automação de testes funcionais ponta a ponta (E2E) com Selenium WebDriver e Playwright.

### 2. Segurança de Aplicações Web e Móveis
- Vetores de ataque comuns (OWASP Top 10): Cross-Site Scripting (XSS), SQL Injection (SQLi), Cross-Site Request Forgery (CSRF).
- Engenharia social, phishing e armadilhas na Web.
- Medidas de mitigação: sanitização estrita, políticas de CSP, cabeçalhos de proteção e Row Level Security (RLS).

### 3. Acessibilidade Digital (WCAG 2.1 AA)
- Diretrizes de acessibilidade: Perceptível, Operável, Compreensível e Robusto.
- Navegação completa por teclado, contrastes mínimos de cor, labels ARIA e compatibilidade com leitores de tela.
- Auditorias automatizadas com Lighthouse, axe-core e Playwright Axe.
