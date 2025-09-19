# Daleel + Citizen Reports Architecture

```mermaid
flowchart LR
    %% Users
    U[Citizen] --> W[Web Dashboard]
    U --> M[Mobile App]

    %% Daleel Core
    W --> B[Backend]
    M --> B
    B --> D[Database]
    B --> AI[Data Science & AI]
    B --> S[Cybersecurity]

    %% Daleel Module
    B --> E[Experience Sharing Module]

    %% Citizen Reports Module
    B --> R[Citizen Reports Module]
    R --> OFF[Officials Dashboard]

    %% Docs & Analytics
    AI --> DOCS[Reports & Insights]
    S --> DOCS
