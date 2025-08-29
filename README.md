aegis-vault/
├── .github/
│   └── workflows/
│       └── ci.yml
├── backend/
│   ├── app/
│   │   ├── api/
│   │   │   ├── __init__.py
│   │   │   ├── deps.py
│   │   │   └── endpoints/
│   │   │       ├── __init__.py
│   │   │       ├── auth.py
│   │   │       ├── files.py
│   │   │       └── shares.py
│   │   ├── core/
│   │   │   ├── __init__.py
│   │   │   └── config.py
│   │   ├── crud/
│   │   │   ├── __init__.py
│   │   │   ├── crud_file.py
│   │   │   └── crud_user.py
│   │   ├── db/
│   │   │   ├── __init__.py
│   │   │   ├── base.py
│   │   │   └── session.py
│   │   ├── models/
│   │   │   ├── __init__.py
│   │   │   ├── audit_log.py
│   │   │   ├── file.py
│   │   │   ├── share.py
│   │   │   └── user.py
│   │   ├── schemas/
│   │   │   ├── __init__.py
│   │   │   ├── file.py
│   │   │   ├── share.py
│   │   │   ├── token.py
│   │   │   └── user.py
│   │   ├── services/
│   │   │   ├── __init__.py
│   │   │   └── s3_service.py
│   │   └── main.py
│   ├── tests/
│   │   ├── __init__.py
│   │   └── test_auth.py
│   ├── Dockerfile
│   └── requirements.txt
├── frontend/
│   ├── lib/
│   │   └── crypto.js
│   ├── components/
│   │   └── UploadComponent.jsx
│   └── ... (standard Next.js or CRA structure)
├── .env.example
├── docker-compose.yml
└── README.md
