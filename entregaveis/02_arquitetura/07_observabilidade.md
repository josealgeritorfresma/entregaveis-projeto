# Plano de Observabilidade

## Objetivo
Detectar falhas rápido, reduzir MTTR e dar visibilidade do comportamento do sistema.

## Logs
- Estruturados (JSON)
- Campos mínimos: level, timestamp, service, traceId, userId (quando permitido), msg

## Métricas
- Latência (p50/p95/pp99)
- Taxa de erros (4xx/5xx)
- Throughput (req/s)
- Uso de recursos (CPU/Mem)

## Tracing
- Propagação de traceId do frontend -> backend
- Span por chamadas externas (DB/HTTP)

## Alertas
- 5xx > X% por Y min
- p95 > limite por Y min
- Falhas de healthcheck
