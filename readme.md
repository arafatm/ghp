---
title: GH-Pages Template 
---

## Deploying
Copy this folder and run `ggit_arafatm; ggit_pages`

Links
- https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions
- https://github.com/marketplace/actions/add-commit

## Useful Links

- [Theme Lanyon](https://lanyon.getpoole.com/)
- https://lanyon.getpoole.com/

## Syntax

### Emoji
> Quote :cry:
> :bulb: bulb :knot:

    Block

### Math

- [Using MathJax](https://codepen.io/josdea/pen/rLOJxL)
- Inline: `$` $ f_{w,b}(x) = wx + b $ is equivalent to 
- Inline: `$$` $$f_{w,b}(x) = wx + b$$ is equivalent to asdf

Block: 
$$
\begin{aligned}
\text{repeat until convergence \{} \\ 
  &w = w - \alpha \frac{\partial}{\partial w} J_{(w,b)}\\
  &b = b - \alpha \frac{\partial}{\partial b} J_{(w,b)}\\
\}
\end{aligned}
$$

| General Notation   | Python | Description                                                                                             |
| :--                | :--    | :--                                                                                                     |
| $w$                | `w`    | parameter: weight                                                                                       |
| $b$                | `b`    | parameter: bias                                                                                         |
| $f_{w,b}(x^{(i)})$ | `f_wb` | The result of the model evaluation at $x^{(i)}$ parameterized by $w,b$: $f_{w,b}(x^{(i)}) = wx^{(i)}+b$ |

### Code

Test Code
```ruby
i = 56;
puts "test #{i}"
```
