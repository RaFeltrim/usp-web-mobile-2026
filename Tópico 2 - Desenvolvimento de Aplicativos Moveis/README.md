# Tópico 2 — Desenvolvimento de Aplicativos Móveis

## 🔗 Recursos e Arquivos de Apoio
- **Slides da Aula 03:** [`Aula 3 - Introdução ao Desenvolvimento de Aplicativos Móveis.pdf`](./Material%20de%20Apoio/Aula%203%20-%20Introdução%20ao%20Desenvolvimento%20de%20Aplicativos%20Móveis.pdf)

---

## 📖 Estrutura Conceitual do Módulo

### 1. Paradigmas de Desenvolvimento Mobile
- **Nativo:** Swift/Kotlin — máxima performance e acesso irrestrito às APIs do hardware, porém custo duplicado de manutenção.
- **Híbrido / Web encapsulado (Cordova/Capacitor):** Camada web executada em WebView com plugins nativos de ponte (*bridge*).
- **Multiplataforma Compilado (React Native / Flutter):** Base única de código com pontes para componentes e widgets nativos.
- **Progressive Web Apps (PWAs):** Aplicações web modernas com Service Workers, manifesto, capacidade offline e experiência app-like sem lojas de aplicativos.

### 2. Critérios de Seleção de Frameworks Multiplataforma
- Análise comparativa multicritério:
  - Curva de aprendizado e ecossistema de bibliotecas.
  - Performance de renderização (60fps) e consumo de memória/bateria.
  - Reutilização de código entre Web e Mobile (Cross-platform coverage).
  - Suporte da comunidade e viabilidade a longo prazo.

### 3. Prototipação UI/UX Mobile-First
- Princípios de usabilidade em telas sensíveis ao toque (touch hitboxes mínimas de 44x44px).
- Safe areas, gestos, transições e micro-interações.
- Prototipagem iterativa no Figma antes da codificação.
