```bash
llm-vps/
├── backend/
│   ├── app/
│   │   ├── api/          # роуты FastAPI
│   │   └── export/       # docx/xlsx генераторы (Арсений)
│   ├── src/
│   │   ├── rag/          # LlamaIndex pipeline (Кирилл + Мария)
│   │   └── llm/          # Ollama client, instructor schemas (Гасов)
│   ├── db/               # PostgreSQL models, migrations (Кирилл)
│   ├── tests/
│   └── Dockerfile
├── docs/                 # Документация проекта
├── frontend/
│   ├── src/
│   │   ├── pages/        # ConsultantPage, AdminPage
│   │   └── components/   # WBSTree, WBSTable, ExportButton
│   └── Dockerfile
├── infra/
│   ├── docker-compose.yml
│   └── nginx.conf
└── .github/workflows/deploy.yml
```
