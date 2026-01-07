# Padrões de Código — Node.js/React/TypeScript

## Typescript
- `strict: true`
- evitar `any`
- tipar retornos de funções críticas

## Backend Node
- Camadas: controller / service / repository (ou outra definida em ADR)
- Validar input na borda (controllers)
- Erros padronizados (handler global)
- Logs estruturados

## Frontend React
- Componentes pequenos e testáveis
- Estado: (A definir: Context/Zustand/Redux)
- Separar: pages / components / hooks / services (API client)
- Acessibilidade: labels, navegação por teclado, contraste

## Qualidade
- Lint + format
- Pre-commit hooks (opcional)
- Cobertura mínima: (A definir)
