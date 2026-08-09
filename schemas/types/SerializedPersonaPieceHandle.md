# SerializedPersonaPieceHandle

`struct`

```mermaid
flowchart LR
  ROOT(["SerializedPersonaPieceHandle"])
  ROOT -->|"PieceId"| string["string"]
  ROOT -->|"PieceType"| persona__PieceType["persona__PieceType"]
  ROOT -->|"PackId"| mce__UUID["mce__UUID"]
  ROOT -->|"IsDefaultPiece"| boolean["boolean"]
  ROOT -->|"ProductId"| string["string"]
```

