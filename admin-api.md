### Login API
```mermaid
    sequenceDiagram
        Admin->>Admin-API: Request login
        Admin-API-->>Admin: Return login result
```

### Add admin API
```mermaid
    sequenceDiagram
        Admin->>Admin-API: Request add admin
        Admin-API-->>Admin: Return add result
```

### Initail parking lot API
```mermaid
    sequenceDiagram
        Admin->>Admin-API: Request init parking lot
        Note over Admin-API: Add slot, near_slots and config to DB
        Admin-API-->>Admin: Return result
```

### Get plate number by car size API
```mermaid
    sequenceDiagram
        Admin->>Admin-API: Request get plate numberss
        Admin-API-->>Admin: Return result
```

### Get slots by car size API
```mermaid
    sequenceDiagram
        Admin->>Admin-API: Request get slots
        Admin-API-->>Admin: Return result
```

### Update parking lot time API
```mermaid
    sequenceDiagram
        Admin->>Admin-API: Request update parking lot time
        Note over Admin-API: Update parking time and clear cache
        Admin-API-->>Admin: Return result
```

### Update parking slot API
```mermaid
    sequenceDiagram
        Admin->>Admin-API: Request update parking slot
        Note over Admin-API: Update parking slot and clear cache
        Admin-API-->>Admin: Return result
```

### Update parking price API
```mermaid
    sequenceDiagram
        Admin->>Admin-API: Request update parking slot
        Note over Admin-API: Update parking price and clear cache
        Admin-API-->>Admin: Return result
```