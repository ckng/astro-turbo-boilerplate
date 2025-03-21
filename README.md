# Astro 5.x + Turborepo boilerplate

This is a boilerplate starter for Astro 5.x project using Turborepo.

## Why Astro?
Astro allow you to use your favorite UI components and libraries. Mix and match React, Preact, Svelte, Vue, SolidJS, AlpineJS, and Lit to build your own website.

## What's inside?

This Turborepo includes the following packages/apps:

### Apps and Packages

- `docs`: a [Astro + Starlight](https://starlight.astro.build) documentation app
- `web`: another [Astro](https://astro.build) app
- `@repo/eslint-config`: `eslint` configurations using [Astro eslint plugin](https://github.com/ota-meshi/eslint-plugin-astro)
- `@repo/typescript-config`: `tsconfig.json`s used throughout the monorepo

### Utilities

This Turborepo has some additional tools already setup for you:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io) for code formatting

### Develop

To develop all apps and packages, run the following command:

```
pnpm install
pnpm dev
```

### Build

To build all apps and packages, run the following command:

```
pnpm build
```

### Remote Caching

> [!TIP]
> Vercel Remote Cache is free for all plans. Get started today at [vercel.com](https://vercel.com/signup?/signup?utm_source=astro-turbo-boilerplate).

Turborepo can use a technique known as [Remote Caching](https://turbo.build/repo/docs/core-concepts/remote-caching) to share cache artifacts across machines, enabling you to share build caches with your team and CI/CD pipelines.

By default, Turborepo will cache locally. To enable Remote Caching you will need an account with Vercel. If you don't have an account you can [create one](https://vercel.com/signup?utm_source=astro-turbo-boilerplate), then enter the following commands:

```
npx turbo login
```

This will authenticate the Turborepo CLI with your [Vercel account](https://vercel.com/docs/concepts/personal-accounts/overview).

Next, you can link your Turborepo to your Remote Cache by running the following command from the root of your Turborepo:

```
npx turbo link
```

## Useful Links

Learn more about Astro:
- [Getting Started](https://docs.astro.build/en/getting-started/)

Learn more about Turborepo:

- [Tasks](https://turbo.build/repo/docs/core-concepts/monorepos/running-tasks)
- [Caching](https://turbo.build/repo/docs/core-concepts/caching)
- [Remote Caching](https://turbo.build/repo/docs/core-concepts/remote-caching)
- [Filtering](https://turbo.build/repo/docs/core-concepts/monorepos/filtering)
- [Configuration Options](https://turbo.build/repo/docs/reference/configuration)
- [CLI Usage](https://turbo.build/repo/docs/reference/command-line-reference)
