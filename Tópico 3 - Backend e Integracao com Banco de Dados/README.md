# Tópico 3 — Backend e Integração com Banco de Dados

## 🔗 Recursos e Arquivos de Apoio
- **Slides da Aula de Backend:** [`backend .pdf`](./Material%20de%20Apoio/backend%20.pdf) *(Prof./Monitor Diego Gomes de Santana)*

---

## 📖 Estrutura Conceitual do Módulo

### 1. Papel da Camada de Backend
- Separação de responsabilidades: lógica de negócios, regras de validação, segurança e orquestração de dados.
- Arquitetura de microsserviços vs. monolitos modulares vs. BaaS (*Backend-as-a-Service*).

### 2. APIs e Protocolos de Comunicação
- Arquitetura RESTful: recursos, URIs semânticas, códigos de status HTTP (2xx, 4xx, 5xx) e contratos JSON.
- Autenticação e Autorização: JWT (*JSON Web Tokens*), cookies seguros (`HttpOnly`, `SameSite`), OAuth 2.0.

### 3. Persistência de Dados e BaaS (Supabase)
- Modelagem relacional em PostgreSQL (chaves primárias, estrangeiras, índices e restrições de integridade).
- Mecanismo de segurança **Row Level Security (RLS)** para autorização declarativa no nível do banco de dados.
- Sincronização em tempo real (*WebSockets/Postgres CDC*) e abstração de endpoints através de clientes tipados.
