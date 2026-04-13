# AI Scheduler

Умный планировщик учебного расписания на базе Claude.

## Запуск

1. Скопируй `GROQ_API_KEY={YOUR_API_KEY}` в `.env` 

2. Запусти:
   ```
   docker compose up --build
   ```

3. Открой http://localhost:8000

## Структура

```
ai-scheduler/
├── backend/
│   ├── main.py          # FastAPI + AI агент
│   ├── static/
│   │   └── index.html   # Весь фронтенд
│   ├── requirements.txt
│   └── Dockerfile
├── docker-compose.yml
└── .env.example
```
