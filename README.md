# nuxt3-hello-world

## Nuxt Minimal Starter

Look at the [Nuxt documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Make sure to install dependencies:

```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install

# bun
bun install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev

# pnpm
pnpm dev

# yarn
yarn dev

# bun
bun run dev
```

## Production

Build the application for production:

```bash
# npm
npm run build

# pnpm
pnpm build

# yarn
yarn build

# bun
bun run build
```

Locally preview production build:

```bash
# npm
npm run preview

# pnpm
pnpm preview

# yarn
yarn preview

# bun
bun run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.

## Prepare

Installing homebrew
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

Installing pnpm
```bash
brew install pnpm
```

```bash
npm ls -g --depth=0

# version check
/Users/username/.nodebrew/node/v22.15.0/lib
├── corepack@0.32.0
├── npm@11.3.0
├── pnpm@10.10.0
└── yarn@1.22.22
```

Create a new Nuxt3 project
```bash
npx nuxi init nuxt3-hello-world
```

Launching Nuxt3 app
```bash
pnpm run dev
```
