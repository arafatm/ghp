---
layout: page
title: GH-Pages Template 
---

<!-- vim-markdown-toc GFM -->

* [Deploying](#deploying)
* [Useful Links](#useful-links)
* [Syntax](#syntax)
  * [Math](#math)
  * [Code](#code)

<!-- vim-markdown-toc -->

## Deploying

Create repo & `ggit_arafatm; ggit_pages`

## Useful Links

- [CloudCannon Academy - Advanced navigation](https://learn.cloudcannon.com/jekyll/advanced-navigation/)
- [CloudCannon Academy - List posts by category](https://learn.cloudcannon.com/jekyll/list-posts-by-category/)
- [GH Pages and Jekyll - GitHub Docs](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)
- [GH Workflows ](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions)
- [GH Workflows: add-commit](https://github.com/marketplace/actions/add-commit)
- [Theme: Lanyon](https://lanyon.getpoole.com/)

## Syntax

**This is bold text**

_This text is italicized_

~~This was mistaken text~~

> Multiline Quote :cry: <newline>
> :bulb: bulb :knot:

    Block Text

```ruby
world = "world"
puts "Hello #{world}"
```

Color `#0969DA`

- [ ] task A
- [ ] :a: task B
- [ ] :b: task C

![](https://media.giphy.com/media/kSbETPzWRAtMEdszqc/giphy.gif)
![](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcTM4eGtoNmlzcWZ3OGZyeXE3aDJqd2N3cjBia2owcTQ1bHZmaXh4bSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ZaEUSTAoWGQDhJumTu/giphy.gif)

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
