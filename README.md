# Wish list (& goals list)

Everything I want, from apple juice to a Lamborghini. Half wish list, half goals board.

A single static page: `index.html`, with no build step and no dependencies apart from Google Fonts.

## Editing the list

All items live in the `tiers` array near the bottom of `index.html`. Each item is:

```js
['Name', 'Description', [['Link label', 'https://...']], 'tag']
```

`tag` is optional: `'ask'` (check with me first), `'gifted'` (someone got it) or `'earned'` (I got it myself).

## Running locally

Open `index.html` in a browser, or:

```sh
npx serve .
```

## Deploying

It's static, so any host works:

- **Vercel:** import the repo with the "Other" framework preset and no build command.
- **GitHub Pages:** Settings → Pages → deploy from the `main` branch, root folder.
