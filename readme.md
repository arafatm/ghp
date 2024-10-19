Wikilinks [[test]]

- `gh workflow run jekyll-gh-pages.yml`
- `gh api --paginate /users/arafatm/repos | jq '.[] | select(.has_pages == true) | .name'`
- Create repo & `ggit_arafatm; ggit_pages`

# Useful Links

- [CloudCannon Academy - Advanced navigation](https://learn.cloudcannon.com/jekyll/advanced-navigation/)
- [CloudCannon Academy - List posts by category](https://learn.cloudcannon.com/jekyll/list-posts-by-category/)
- [GH Pages and Jekyll - GitHub Docs](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)
- [GH Workflows ](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions)
- [GH Workflows: add-commit](https://github.com/marketplace/actions/add-commit)
- [Theme: Lanyon](https://lanyon.getpoole.com/)

# Syntax

## Text

### Block
    Block Text Block Text Block Text Block Text Block Text Block Text Block Text Block Text Block Text Block Text Block Text Block Text Block Text Block Text Block Text Block Text Block Text Block Text

> Multiline Quote :cry: <newline>
> :bulb: :bulb: :knot:

#### Details
<details><summary>:bulb: Testing Code</summary></details>

#### Code
```ruby
world = "world"
puts "Hello #{world}"
```

#### Color
Color `#0969DA`

#### Emoji
:bulb:


This is some random text **This is bold text** _This text is italicized_ ~~This
was mistaken text~~ This is some random text **This is bold text** _This text
is italicized_ ~~This was mistaken text~~ This is some random text **This is
bold text** _This text is italicized_ ~~This was mistaken text~~ This is some
random text `with some code in the middle` **This is bold text** _This text is
italicized_ ~~This was mistaken text~~ This is some random text **This is bold
text** _This text is italicized_ ~~This was mistaken text~~ This is some random
text **This is bold text** _This text is italicized_ ~~This was mistaken text~~

### Tasks

- [ ] task A
- [ ] :a: task B
- [ ] :b: task C

### Images

![](https://images.unsplash.com/photo-1493612276216-ee3925520721)
![](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcTM4eGtoNmlzcWZ3OGZyeXE3aDJqd2N3cjBia2owcTQ1bHZmaXh4bSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ZaEUSTAoWGQDhJumTu/giphy.gif)
![](https://media.giphy.com/media/kSbETPzWRAtMEdszqc/giphy.gif)
![](https://media.giphy.com/media/kSbETPzWRAtMEdszqc/giphy.gif) 
Followed by some text Followed by some text on next line 

#### Images w/ text
![](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcTM4eGtoNmlzcWZ3OGZyeXE3aDJqd2N3cjBia2owcTQ1bHZmaXh4bSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ZaEUSTAoWGQDhJumTu/giphy.gif)
- followed by bullets

![](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcTM4eGtoNmlzcWZ3OGZyeXE3aDJqd2N3cjBia2owcTQ1bHZmaXh4bSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ZaEUSTAoWGQDhJumTu/giphy.gif)
followed by paragraph
![](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcTM4eGtoNmlzcWZ3OGZyeXE3aDJqd2N3cjBia2owcTQ1bHZmaXh4bSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ZaEUSTAoWGQDhJumTu/giphy.gif) 
### Math

- [Using MathJax](https://codepen.io/josdea/pen/rLOJxL)
- Inline: `$` $f_{w,b}(x) = wx + b$ is equivalent to 
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

## Long Long Long Long Long Long Long Heading 2
### Heading 3
text
- followed by list
  - 2nd order
- followed by list
### Heading 3
### Heading 3
### Heading 3
### Heading 3
### Heading 3
### Heading 3
### Heading 3
### Heading 3
### Heading 3
### Heading 3
### Heading 3
### Heading 3
#### Heading 4
text
##### Heading 5
text
###### Heading 6
text

## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## Heading 2
### Heading Heading 3 
#### Heading Heading 4 Heading
##### Heading 5 Heading Heading Heading
###### Heading 6 Heading Heading Heading Heading

## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

