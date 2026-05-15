## 📡 API Endpoints

### GET /api/health
Returns system status

Response:
{
  "status": "ok"
}

---

### POST /api/login
Login user

Request:
{
  "email": "test@example.com",
  "password": "123456"
}

Response:
{
  "token": "jwt_token_here"
}