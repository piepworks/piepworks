# Piepworks Homepage

## Work on it

Set things up:

- [Install Browsersync](https://browsersync.io/)
- [Install Tailwind CLI](https://tailwindcss.com/blog/standalone-cli)

Run these in two different Terminal tabs:

- `tailwindcss -i ./tailwind.css -o ./public/main.css --watch`
- `browser-sync start --server "public" --files "public" --no-open`

## Deploy it

Make sure this is in the deploy script:

```shell
npx tailwindcss -i ./tailwind.css -o ./public/main.css --minify
```
