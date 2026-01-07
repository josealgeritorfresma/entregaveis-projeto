# Parâmetros e Segredos

## Princípios
- Nunca commitar segredos no repositório
- Usar variáveis de ambiente / secret manager
- Rotacionar chaves periodicamente

## Lista de variáveis (exemplo)
### Backend
| Nome | Tipo | Obrigatório | Exemplo | Observação |
|---|---|---:|---|---|
| DATABASE_URL | segredo | sim | postgres://... |  |
| JWT_SECRET | segredo | sim | *** |  |
| PORT | parâmetro | não | 3000 |  |

### Frontend
| Nome | Tipo | Obrigatório | Exemplo | Observação |
|---|---|---:|---|---|
| VITE_API_BASE_URL | parâmetro | sim | https://api... | não é segredo |
