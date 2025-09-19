# Daleel — Architecture

```mermaid
flowchart LR
    U[👤 User] --> W[🌐 Web Dashboard]
    U --> M[📱 Mobile App (Flutter)]
    W --> B[⚙️ Backend (API)]
    M --> B
    B --> D[🗄 Database (MongoDB / Postgres)]
    B --> AI[🤖 Data Science & AI]
    B --> S[🔐 Cybersecurity & Monitoring]
    AI --> DOCS[📑 Reports & Insights]
    S --> DOCS
