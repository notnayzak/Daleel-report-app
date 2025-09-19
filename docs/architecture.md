# 📊 System Flowchart

```mermaid
flowchart LR
    U[👤 User] --> W[🌐 Web Dashboard]
    U --> M[📱 Mobile App (Flutter)]
    W --> B[⚙️ Backend (API + Logic)]
    M --> B
    B --> D[🗄 Database (MongoDB / Postgres)]
    B --> AI[🤖 Data Science & AI\n(Sentiment Analysis, Insights)]
    B --> S[🔐 Cybersecurity & Network\n(Security Audits, Pen Testing)]
    AI --> DOCS[📑 Documentation & Reports]
    S --> DOCS

