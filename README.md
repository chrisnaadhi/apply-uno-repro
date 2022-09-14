# Nuxt 3 with @apply UnoCSS not built properly in build & preview mode

## Reproduction

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## Run the Dev Mode

Start the development server on http://localhost:3000
it was perfectly fine on dev mode

```bash
npm run dev
```

## UnoCSS not built properly in Build Mode & Preview

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

you can try with stackblitz :
[Stackblitz Repro](https://stackblitz.com/github/chrisnaadhi/apply-uno-repro)
