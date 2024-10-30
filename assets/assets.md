# ASSETS
Here's another type showing a more detailed production pipeline:

```markdown
```mermaid
sequenceDiagram
    autonumber
    participant C as Client
    participant P as Producer
    participant AI as AI Engine
    participant E as Editor
    
    rect rgb(200, 220, 255)
        Note over C,AI: Pre-Production Phase
        C->>P: Project requirements
        P->>AI: Initialize AI models
        AI-->>P: Model readiness confirmation
    end
    
    rect rgb(200, 255, 220)
        Note over P,E: Production Phase
        P->>AI: Generate visual assets
        AI-->>P: Initial renders
        P->>C: Review first draft
        C-->>P: Feedback
    end
    
    rect rgb(255, 220, 220)
        Note over AI,E: Post-Production
        P->>E: Final assets
        E->>C: Deliver final cut
    end
[Back Home](/) |  [DOCS](/docs/) |  [SRC](/src/)

