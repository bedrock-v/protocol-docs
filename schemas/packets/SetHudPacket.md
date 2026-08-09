# SetHudPacket

`packet` - id **308**

This packet will toggle the HUD visibility.

```mermaid
flowchart LR
  ROOT(["SetHudPacket"])
  ROOT -->|"Hud Element"| HudElement["HudElement[]"]
  ROOT -->|"Hud Visible"| HudVisibility["HudVisibility"]
```

