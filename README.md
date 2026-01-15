# ServeRest – Test Automation Project

Projeto de testes automatizados para a API e Front-end do **ServeRest**, com foco em validação funcional, integração e testes end-to-end, utilizando boas práticas de QA e automação moderna.

---

## Objetivo

Garantir a qualidade das principais funcionalidades do sistema ServeRest por meio de:
- Testes de API (contratos, regras de negócio e fluxos críticos)
- Testes End-to-End no Front-end
- Automação escalável e reutilizável
- Execução local e preparada para CI/CD

---

## Escopo de Testes

### Funcionalidades cobertas
- Autenticação de usuários
- Gerenciamento de usuários
- Gerenciamento de produtos
- Fluxos de compra e carrinho
- Validações de regras de negócio
- Integração entre API e Front-end

### Tipos de teste
- Testes funcionais
- Testes de API (REST)
- Testes End-to-End (E2E)
- Testes de regressão automatizados

---

## Tecnologias Utilizadas

- **Node.js**
- **Playwright**
- **JavaScript**
- **GitHub Actions** (CI)

---

## Estrutura do Projeto

```text
docs/
 ├─ test-strategy.md
 ├─ test-plan.md
 └─ test-scenarios.md

automation/
 ├─ api/
 ├─ e2e/
 ├─ pages/
 ├─ services/
 └─ tests/

.github/
 └─ workflows/

README.md