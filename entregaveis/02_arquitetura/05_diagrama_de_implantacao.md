# Diagrama de Implantação

## Ambientes
- dev
- homolog
- prod

## Componentes em produção
- CDN/Static hosting (frontend)
- API (container)
- DB
- Cache (opcional)
- Queue (opcional)

## Diagrama (placeholder)
```mermaid
flowchart TB
  DNS-->CDN[CDN/Static Hosting]
  CDN-->FE[React Build]
  FE-->API[Node API]
  API-->DB[(DB)]
```
