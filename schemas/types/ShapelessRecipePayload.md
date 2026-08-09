# ShapelessRecipePayload

`struct`

```mermaid
flowchart LR
  ROOT(["ShapelessRecipePayload"])
  ROOT -->|"Recipe Id"| string["string"]
  ROOT -->|"Ingredients"| RecipeIngredient["RecipeIngredient[]"]
  ROOT -->|"Results"| NetworkItemInstanceDescriptorData["NetworkItemInstanceDescriptorData[]"]
  ROOT -->|"UUID"| mce__UUID["mce__UUID"]
  ROOT -->|"Tag"| string["string"]
  ROOT -->|"Priority"| int32["int32"]
  ROOT -->|"Unlocking Requirement"| RecipeUnlockingRequirement["RecipeUnlockingRequirement"]
  ROOT -->|"Net Id"| RecipeNetId["RecipeNetId"]
```

