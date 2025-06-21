## 📊 Workflow Diagram

```mermaid
flowchart LR
    A[Biometric Machine - CSV Export] --> B[Read CSV and Preprocess]
    B --> C[Azure GPT]
    C --> E[Google Sheet]
    E --> C
    E --> F[Telegram Bot Q&A]
    C --> F
    E --> G[Email Notifications to HR and Employees]
    C --> G
