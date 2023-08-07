---
title: GH-Pages Template 
---

> :cry: Quote

:bulb: bulb :knot:

    Block

## Math

- `$` $` f_{w,b}(x) = wx + b `$ is equivalent to 
- `$` $ f_{w,b}(x) = wx + b $ is equivalent to 
- `$$` $$f_{w,b}(x) = wx + b$$ is equivalent to asdf
- `$$` $$ f_{w,b}(x) = wx + b $$ is equivalent to asdf

$$
\begin{aligned}
\text{repeat until convergence \{} \\ 
  &w = w - \alpha \frac{\partial}{\partial w} J_{(w,b)}\\
  &b = b - \alpha \frac{\partial}{\partial b} J_{(w,b)}\\
\}
\end{aligned}
$$


```
$$
\begin{aligned}
\text{repeat until convergence \{} \\ 
  &w = w - \alpha \frac{\partial}{\partial w} J_{(w,b)}\\
  &b = b - \alpha \frac{\partial}{\partial b} J_{(w,b)}\\
\}
\end{aligned}
$$
```

| General Notation       | Python (if applicable) | Description                                                                                                   |
| :--                    | :--                    | :--                                                                                                           |
| $`w`$                  | `w`                    | parameter: weight                                                                                             |
| $`b`$                  | `b`                    | parameter: bias                                                                                               |
| $`f_{w,b}(x^{(i)})`$   | `f_wb`                 | The result of the model evaluation at $`x^{(i)}`$ parameterized by $`w,b`$: $`f_{w,b}(x^{(i)}) = wx^{(i)}+b`$ |

## Testing

Copy this folder and run `ggit_arafatm; ggit_pages`

Links
- https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions
- https://github.com/marketplace/actions/add-commit

## Code

Test Code
```ruby
i = 56;
puts "test #{i}"
```
