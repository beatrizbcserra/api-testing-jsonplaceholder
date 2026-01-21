# 🧪 Automação de Testes de API - JSONPlaceholder

Este projeto contém uma suíte de testes automatizados desenvolvida para a API [JSONPlaceholder](https://jsonplaceholder.typicode.com/), uma API REST fake para testes e prototipagem. 

O objetivo principal foi aplicar boas práticas de QA, garantindo a integridade dos dados, a performance e a resiliência dos endpoints.

## 🛠️ Tecnologias Utilizadas
* **Postman:** Ferramenta para desenvolvimento e execução dos testes.
* **JavaScript:** Linguagem utilizada nos scripts de pré-requisição e pós-resposta.

## 📋 Estrutura da Suíte de Testes

Os testes foram organizados em pastas seguindo uma estratégia de pirâmide de testes para APIs:

1. **01 - Smoke Tests:** Validações básicas de conectividade e status code (200 OK).
2. **02 - Functional Tests:** Verificação das operações de CRUD (GET, POST, PUT, DELETE) e lógica de negócio.
3. **03 - Schema Validation:** Garantia de que o contrato da API (estrutura do JSON) está correto.
4. **04 - Negative Tests:** Validação de mensagens de erro e comportamentos inesperados (404 Not Found, etc).

## 🚀 Como Executar os Testes

Para rodar este projeto localmente, siga os passos abaixo:

1. **Clone este repositório:**
   ```bash
   git clone [https://github.com/beatrizbcserra/api-testing-jsonplaceholder.git](https://github.com/beatrizbcserra/api-testing-jsonplaceholder.git)
