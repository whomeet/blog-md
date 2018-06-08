# md-shell

## USAGE

```bash
yarn global add md-shell

# deploy
md deploy -u <github userName> -p <vuepress docs dir> -r <github repository address>
# example
md deploy -u blog -p docs -r blog.github.io

# new post article
md post -p <file path> --page <filename>
# example
md post -p docs/hello --page index.md
```