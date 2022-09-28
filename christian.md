# Welcome

to Git and Mermdaid

```mermaid
sequenceDiagram
  participant StarterApp
  participant GameApp
  participant Registration
  participant Database
  StarterApp->>+Registration: Request Start
  Registration->>-Database: Write Start Request
  Registration->>+GameApp: Start Game
  GameApp->>-Registration: Return Game Information
  Registration->>+Database: Write Game Information
```
