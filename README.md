# blog-md

## USAGE

```bash
yarn global add blog-md

# deploy
md deploy -u <github userName> -p <vuepress docs dir> -r <github repository address>
# example
md deploy -u bloss -p docs -r bloss.github.io

# new post article
md post -p <file path> --page <filename>
# example
md post -p docs/hello --page index.md
```