# Plano de Testes

## 1. Objetivo
Garantir qualidade funcional e não funcional para frontend (React) e backend (Node).

## 2. Escopo
### Inclui
- Testes unitários (frontend e backend)
- Integração (API + DB/mocks)
- E2E (fluxos críticos)
- Regressão básica antes de release

### Não inclui (inicialmente)
- (A definir)

## 3. Estratégia por camada (sugestão)
- **Backend**: Jest/Vitest + supertest
- **Frontend**: Testing Library + Vitest/Jest
- **E2E**: Playwright/Cypress

## 4. Ambiente
- dev/homolog com dados de teste controlados
- seeds/mocks

## 5. Critérios de entrada/saída
- Entrada: build ok, ambiente ok, histórias prontas
- Saída: taxa de sucesso >= X%, sem bugs críticos abertos

## 6. Gestão de defeitos
- Severidade: baixa/média/alta/crítica
- SLA de correção: (A definir)
