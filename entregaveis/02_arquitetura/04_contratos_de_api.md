# Contratos de API (API Contracts)

## Padrões
- Base URL: `/api`
- Versionamento: `/v1`
- Formato: JSON
- Erros: `code`, `message`, `details`, `traceId`

## Exemplo de erro
```json
{
  "code": "VALIDATION_ERROR",
  "message": "Campo inválido",
  "details": [{"field":"email","reason":"formato inválido"}],
  "traceId": "..."
}
```

## Endpoint template
### <MÉTODO> /api/v1/<recurso>
**Descrição**:
**Auth**: Público | Bearer JWT | API Key
**Request**:
```json
{}
```
**Response 200**:
```json
{}
```
