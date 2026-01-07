# Plano de Rollback

## Quando fazer rollback
- Erro 5xx > X% por Y min
- p95 acima do limite por Y min
- Falha em smoke test
- Incidente SEV1/SEV2 confirmado

## Como fazer rollback
1. Reverter release do frontend para versão anterior
2. Reverter backend (imagem/tag anterior)
3. Reverter migrations (se suportado) ou aplicar forward-fix
4. Validar smoke tests

## Validação pós-rollback
- API ok
- Fluxo crítico ok
- Métricas estabilizadas
