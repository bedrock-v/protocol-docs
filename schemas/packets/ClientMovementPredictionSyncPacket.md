# ClientMovementPredictionSyncPacket

`packet` - id **322**

Only used in Server-Authoritative Movement. Sent periodically if the client has received corrections from the server. Contains information about client-predictions that are relevant to movement.

```mermaid
flowchart LR
  ROOT(["ClientMovementPredictionSyncPacket"])
  ROOT -->|"Actor Data Flag"| ActorDataFlagComponent["ActorDataFlagComponent"]
  ROOT -->|"Actor Bounding Box"| ActorDataBoundingBoxComponent["ActorDataBoundingBoxComponent"]
  ROOT -->|"Movement Attributes"| MovementAttributesComponent["MovementAttributesComponent"]
  ROOT -->|"Actor Unique ID"| ActorUniqueID["ActorUniqueID"]
  ROOT -->|"Actor Flying State"| boolean["boolean"]
```

