# Qwik + SST Templates Mono-Repo

This repository contains templates for various Qwik sites utilizing SST for deployment.

## Templates

- [Qwik in SSR Mode](./templates/qwik-ssr/) - Primarily server-side rendered Qwik site deployed with SST.

## Dev

To run all templates in parallel:

```
npm run dev
```

To run a specific template:

```
npm run dev:ssr
```

## Build

To build all templates in parallel:

```
npm run build
```

To build a specific template:

```
npm run build:ssr
```

To force a rebuild of a template (useful when dependencies change):

```
npm run build -- --force
npm run build:ssr -- --force
```

## Deploy

To deploy all templates in parallel:

```
npm run deploy
```

To deploy a specific template:

```
npm run deploy:ssr
```
