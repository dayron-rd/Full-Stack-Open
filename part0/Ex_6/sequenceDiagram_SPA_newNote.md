```mermaid
sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    server-->>browser: JSON [{ "content": "Ex_6", "date": "2024-10-22" }, ... ]
    deactivate server

```

