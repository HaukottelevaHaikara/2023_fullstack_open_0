    sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    server->>browser: {content: "b", date: "2023-12-22T18:14:23.357Z"}
    deactivate server
