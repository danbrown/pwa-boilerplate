# PWA React Boilerplate

PWA basic setup and functions using React

## Usage

```sh
npm run build
```

or

```sh
yarn run build
```

then

```sh
npx serve build
```

## Assets

Replace the `./public/logo.png` and `./public/favicon.png` files.
Then delete `./public/icons` folder.

Run to generate new assets.
`manifest.json` file is already configured to use this icons.

```sh
npx pwa-asset-generator ./public/logo.png ./public/icons
```
