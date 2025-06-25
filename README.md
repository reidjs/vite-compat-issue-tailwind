# vite-compat-issue-tailwind

How to reproduce error:

1. fork and clone this repo

2. cd to repo and `npm install`

3. run `npm install tailwindcss @tailwindcss/vite`


You should see an error like this: 

```sh
➜  vite-compat-issue-tailwind npm install tailwindcss @tailwindcss/vite

npm error code ERESOLVE
npm error ERESOLVE unable to resolve dependency tree
npm error
npm error While resolving: vite-compat-issue-tailwind@0.0.0
npm error Found: vite@7.0.0
npm error node_modules/vite
npm error   dev vite@"^7.0.0" from the root project
npm error
npm error Could not resolve dependency:
npm error peer vite@"^5.2.0 || ^6" from @tailwindcss/vite@4.1.10
npm error node_modules/@tailwindcss/vite
npm error   @tailwindcss/vite@"*" from the root project
npm error
npm error Fix the upstream dependency conflict, or retry
npm error this command with --force or --legacy-peer-deps
npm error to accept an incorrect (and potentially broken) dependency resolution.
npm error
```



## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```
