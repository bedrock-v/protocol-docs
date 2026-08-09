# ShowStoreOfferPacket

`packet` - id **91**

The server can redirect the user to a 3rd party server page, to a marketplace offer description page, or to a dressing room page containing desired offer.

```mermaid
flowchart LR
  ROOT(["ShowStoreOfferPacket"])
  ROOT -->|"Offer Id"| mce__UUID["mce__UUID"]
  ROOT -->|"Redirect Type"| ShowStoreOfferRedirectType["ShowStoreOfferRedirectType"]
```

