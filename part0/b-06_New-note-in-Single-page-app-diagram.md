sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/spa
    server-->>browser: {"message":"note created"}
    activate server
    deactivate server
