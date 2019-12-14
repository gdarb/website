# Hugo Website
Repository used to store all Hugo information for gdarb.github.io

Generated `public` folder from Hugo is the submodule `gdarb/gdarb.github.io`

Use the below command to strip the `public` folder of all non-essential files
before rebuilding the site with `hugo` (**note:** run this command from the
root, not inside `public`)

```sh
find public ! -name README.md ! -name LICENCE.md ! -name _config.yml ! -name CNAME ! -name .gitignore ! -name .git -delete
```
