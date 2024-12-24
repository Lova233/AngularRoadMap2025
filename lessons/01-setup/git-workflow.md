# Il Nostro Workflow Git Semplificato 🌳

flowchart TD
    ReadMe[ReadMe Documentation] --> Guides[Guides]
    ReadMe --> APIRef[API Reference]
    
    Guides --> Editor[Editor UI]
    Editor --> Slash[Slash Commands]
    Slash --> Mermaid[Mermaid Diagrams]
    Slash --> Other[Other Blocks]
    
    APIRef --> OpenAPI[OpenAPI Spec]
    APIRef --> Manual[Manual Editor]
    
    style ReadMe fill:#f9f,stroke:#333,stroke-width:4px
    style Mermaid fill:#bbf,stroke:#333,stroke-width:2px


## I Soli Comandi Che Useremo 🛠️

1. `git add .` - Prepara TUTTE le modifiche
2. `git commit -m "messaggio"` - Salva le modifiche
3. `git push` - Condividi su GitHub

Questo è tutto quello che ci serve per ora! 🎉
