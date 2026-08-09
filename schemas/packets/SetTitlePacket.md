# SetTitlePacket

`packet` - id **88**

There are 2 commands associated with it: title and titleraw.
	Both of which have functionality to change fade in/out time for titles, sub titles, and action bar text.
	titleraw is using json to format so it will be bigger (i don't have an example)

```mermaid
flowchart LR
  ROOT(["SetTitlePacket"])
  ROOT -->|"Title Type"| SetTitlePacket_TitleType["SetTitlePacket_TitleType"]
  ROOT -->|"Title Text"| string["string"]
  ROOT -->|"Fade In Time"| int32["int32"]
  ROOT -->|"Stay Time"| int32["int32"]
  ROOT -->|"Fade Out Time"| int32["int32"]
  ROOT -->|"Xuid"| string["string"]
  ROOT -->|"Platform Online Id"| string["string"]
  ROOT -->|"Filtered Title Message"| string["string"]
```

