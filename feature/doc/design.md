# Design: Add to Cart

*Linked issues: #1, #2*

## Sketch

```
[Apple - $2]   [Add to Cart]
[Bread - $4]   [Add to Cart]

   Cart: 2 items
```

## Data flow

- **Input:** [what triggers this? what data comes in?]
- **Process:** [what happens internally?]
- **Output:** [what does the user see change?]

## Design decisions

- Cart stored in a JavaScript array (not localStorage — out of scope for v1)
- Cart count shown as plain digits, no styling required
- One Add to Cart button per product (no quantity selector)
- Click adds 1 each time; no decrement option in this version
