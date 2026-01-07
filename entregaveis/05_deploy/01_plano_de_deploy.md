# Plano de Deploy

## 1. Estratégia
- ( ) Rolling
- ( ) Blue/Green
- ( ) Canary
- ( ) Manual

## 2. Pré-requisitos
- Build do frontend gerado
- Imagem/container do backend publicado (se aplicável)
- Migrações de banco planejadas
- Variáveis e segredos configurados

## 3. Passo a passo (exemplo)
1. Congelar merge (janela de release)
2. Rodar pipeline CI/CD
3. Aplicar migrations
4. Publicar backend
5. Publicar frontend (CDN)
6. Smoke tests
7. Liberar tráfego (se canary/blue-green)

## 4. Pós-deploy
- Verificar métricas/alertas por 30-60min
