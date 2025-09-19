# Daleel — Architecture

```mermaid
flowchart LR
    U["👤 User"] --> W["🌐 Web Dashboard"]
    U --> M["📱 Mobile App (Flutter)"]
    W --> B["⚙️ Backend (API + Logic)"]
    M --> B
    B --> D["🗄️ Database (MongoDB / Postgres)"]
    B --> AI["🤖 Data Science & AI (Sentiment Analysis, Insights)"]
    B --> S["🔐 Cybersecurity & Network (Security Audits, Pen Testing)"]
    AI --> DOCS["📄 Documentation & Reports"]
    S --> DOCS
