# ClientCacheMissResponsePacket

`packet` - id **136**

Any missing blob should just be thrown into one of these packet ASAP and sent. This is actually how chunk data gets to the client the first time.

```mermaid
flowchart LR
  ROOT(["ClientCacheMissResponsePacket"])
  ROOT -->|"Missing Blobs"| MissingBlobData["MissingBlobData[]"]
```

