flowchart LR
    subgraph Data_Input
      A1[Biometric Machine\n(CSV Export)]
    end

    subgraph Processing_Pipeline
      B1[Read CSV\n& Preprocess]
      B2[Classify Attendance\n(via Azure GPT)]
      B3[Map to Calendar View\n(Pandas)]
      B4[Write to\nGoogle Sheet]
    end

    subgraph Outputs
      C1[Telegram Bot Q&A]
      C2[Email Notifications\n(HR & Employees)]
    end

    A1 --> B1 --> B2 --> B3 --> B4
    B4 --> C1
    B4 --> C2

    click C1 href "https://github.com/YOUR_USERNAME/attendance-ai-agent#telegram-bot" "Telegram Bot Details"
    click C2 href "https://github.com/YOUR_USERNAME/attendance-ai-agent#email-feature" "Email Automation Details"
