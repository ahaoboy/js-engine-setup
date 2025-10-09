# js-engine-setup

```yml
- uses: easy-install/js-engine-setup@v1
  env:
    # need for https://api.github.com/repos/denoland/deno/releases/latest
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```