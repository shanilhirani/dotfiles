## lazy install of packages

```bash
for package in $(cat pipx.txt); pipx install $package
```