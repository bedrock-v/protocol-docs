# MessageAndParams

`struct`

```mermaid
flowchart LR
  ROOT(["MessageAndParams"])
  ROOT -->|"Message Type"| uint8["uint8"]
  ROOT -->|"Message"| string["string"]
  ROOT -->|"Parameter List"| string["string[]"]
```

