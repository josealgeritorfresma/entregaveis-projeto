# Segurança e Ameaças (Threat Modeling resumido)

## Ativos
- Dados pessoais (LGPD)
- Credenciais/tokens
- Dados de negócio

## Ameaças comuns (checklist)
- Injeção (SQL/NoSQL)
- XSS / CSRF
- Broken Access Control (IDOR)
- Vazamento de segredos
- Dependências vulneráveis

## Controles mínimos recomendados (Node/React)
- Helmet (headers) no backend
- Validação de entrada (zod/joi/class-validator)
- Rate limit / proteção brute-force
- Sanitização/escaping no frontend
- SAST/Dependency scanning no CI
- Segredos via vault/variables do ambiente (nunca no repo)

## Requisitos de auditoria/log
- Logar: autenticação, erros, ações sensíveis
- Não logar: senha, tokens, PII sensível
