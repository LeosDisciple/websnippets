# Architecture
```mermaid
graph TD
    A1[Client Browser] --> C[REST Endpoint\nPHP Server]
    A2[Client Application] --> C
    C --> D[Files saved in \n File Directory]
    C --> E[MariaDB \n Database]
```
