# HackUPC organizers recluiting page

[![Netlify Status](https://api.netlify.com/api/v1/badges/35f0719a-3232-4408-a714-48aa164f5b90/deploy-status)](https://app.netlify.com/sites/hackupc-recruiting/deploys)
[![CI](https://github.com/hackupc/recruiting-landing/actions/workflows/ci.yml/badge.svg)](https://github.com/hackupc/recruiting-landing/actions/workflows/ci.yml)

![HackUPC landing preview](src/assets/ogimage.png)

Hi! This is the code of the recruiting organizers landing page of HackUPC

## Develop

Clone the repo, install [Node](https://nodejs.org/en/download/) and [Yarn](https://yarnpkg.com/), and run `yarn install` the first time:

```sh
git clone git@github.com:hackupc/recruiting-landing.git
cd hackupc-landing

npm install -g yarn

yarn install
```

Use `yarn start` to compile and serve the build directory in real-time. It reloads every time there's a change. Then view the website at [https://localhost:3000](https://localhost:3000)

```sh
yarn start
```

Whenever you want, fix auto-fixable lint errors and format files:

```sh
  yarn run lint:eslint
  yarn run lint:stylelint
  yarn run lint:prettier
```

From while to while, update the dependencies with this command:

```sh
  yarn upgrade-interactive
```

### Tips

- **Use `VS code`**, there's the `.vscode` folder with a good workspace configuration. It will be applied automatically.
- Install `ESlint` and `Prettier` extensions.

> If you're unfamiliar with modern vanilla websites, check [this video from CodelyTV](https://youtu.be/ZMBh6n3KWhY) (in Spanish) to understand the reasoning and benefits of this kind of architectures.

## Deploy

**Push to master**. [Netlify](https://app.netlify.com/sites/hackupc) will build and deploy automatically.

If you push something that doesn't build, don't worry, it won't be published.

## Support

If you need help understanding something of this repo you can ask the previous developers. The ones that made the 2022 edition are:

- Carlota Catot Bragòs: Slack `@Carlota` [carlotacb.dev](https://carlotacb.dev)
- Maurici Abad Gutierrez: Slack `@mauri` [mauriciabad.com](https://mauriciabad.com/)

## License

MIT © Hackers@UPC
