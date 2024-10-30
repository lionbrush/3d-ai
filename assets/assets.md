# ASSETS
```mermaid
sequenceDiagram
    participant A as Artist
    participant P as Pre-Production
    participant AI as AI Tools
    participant R as Rendering
    participant PP as Post-Production

    A->>P: Define concept & style
    P->>AI: Input style parameters
    AI->>AI: Generate initial assets
    AI-->>A: Review generated content
    A->>AI: Refine parameters
    AI->>R: Export final assets
    R->>PP: Process rendered frames
    PP->>A: Final review
    A->>PP: Approval/revisions

[Back Home](/) |  [DOCS](/docs/) |  [SRC](/src/)

