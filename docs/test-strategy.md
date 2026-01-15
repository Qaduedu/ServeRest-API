# 1. Escopo

## Features essenciais: 

###Autenticação e Autorização, Consulta de Saldo, Criação de Transações Financeiras, Listagem de Transações, Transferência entre Contas, Validações e Tratamento de Erros, Segurança Básica e Acesso Indevido.
Todas as features serão testadas prioritariamente em nível de API, com possibilidade de testes End-to-End quando houver interface web disponível.

2. Tipos de Teste Aplicados

Testes Funcionais (API)
Testes de Regressão
Testes de Smoke
Testes de Contrato (API)
Testes Negativos
Testes End-to-End (quando aplicável)

3. Estratégia por Feature

Autenticação: testes positivos, negativos, validação de token e expiração.
Saldo: validação de resposta correta, permissões e consistência.
Transações: regras de negócio, valores válidos/ inválidos.
Listagem: paginação, histórico e integridade dos dados.
Transferências: fluxo completo, saldo insuficiente, contas inválidas.
Validações: mensagens de erro, status HTTP corretos.
Segurança: acesso sem token, token inválido, usuário não autorizado.

4. Automação
A automação será baseada em Node.js utilizando frameworks de testes de API e E2E. Os testes automatizados serão integrados ao CI para execução contínua.