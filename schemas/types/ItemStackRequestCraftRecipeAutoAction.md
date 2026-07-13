# ItemStackRequestCraftRecipeAutoAction

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["ItemStackRequestCraftRecipeAutoAction"])
  ROOT -->|"Action type"| ItemStackRequestActionType["ItemStackRequestActionType"]
  ROOT -->|"Recipe Net Id"| RecipeNetId["RecipeNetId"]
  ROOT -->|"Number of requested crafts"| uint8["uint8"]
  ROOT -->|"Ingredients"| RecipeIngredient["RecipeIngredient[]"]
```

