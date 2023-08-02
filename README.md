Uma fake API para envio de email

Base URL: https://contact-fake-api.onrender.com

## ROTAS

### Salvar email /emails POST

Padrão de corpo

```json
{
   "name": "John Doe",
   "email": "email@example.com",
   "departament": "Ensino",
   "message": "Mensagem"
}
```

Padrão de resposta

```json
{
   "id": 1,
   "name": "John Doe",
   "email": "email@example.com",
   "departament": "Ensino",
   "message": "Mensagem"
}
```
