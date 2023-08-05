Stuff to include as `git submodule add ghp.template` for all my `http://arafatm.github.io/*`

To enable GH-Pages
```bash
gh api --method PUT -H "Accept: application/vnd.github+json" -H "X-GitHub-Api-Version: 2022-11-28" \
  /repos/arafatm/$(basename $(pwd))/actions/workflows/ghp.yml/enable
```

```ruby
puts "test code block"
```
