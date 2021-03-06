title: CSS Spacing Classes
---
There are CSS classes supplied by Quasar to help you with spacing for DOM elements or components.

## Syntax
```
q-[p|m][t|r|b|l|a|x|y]-[none|xs|sm|md|lg|xl]
    T       D                   S

T - type
  - values: p (padding), m (margin)

D - direction
  - values:
      t (top), r (right), b (bottom), l (left),
      a (all), x (both left & right), y (both top & bottom)

S - size
  - values:
      none,
      xs (extra small),
      sm (small),
      md (medium),
      lg (large),
      xl (extra large)
```

## Examples

```html
<!-- small padding in all directions -->
<div class="q-pa-sm">...</div>

<!-- medium margin to top, small margin to right -->
<q-card class="q-mt-md q-mr-sm">...</q-card>
```
