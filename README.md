# Svelte Kitify

A template for Svelte Kit `&&` Netlify

⚠ **SvelteKit is currently in public beta**. This template and its API may change drastically in the next few months.

last tested working versions (as of 3/15/2021):
- `@sveltejs/adapter-netlify` 1.0.0-next.3
- `@sveltejs/kit` 1.0.0-next.49
- `vite` 2.1.0

Command to use template: `npx degit armchair-traveller/svelte-kitify`

_below are instructions included with the default Svelte Kit template_

---

# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte);

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm init svelte@next

# create a new project in my-app
npm init svelte@next my-app
```

> Note: the `@next` is temporary

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

Svelte apps are built with _adapters_, which optimise your project for deployment to different environments, like [Begin](https://begin.com), [Netlify](https://www.netlify.com), [Vercel](https://vercel.com) and so on. (You can also create your own adapter — instructions TODO.)

By default, `npm run build` will generate a Node app that you can run with `node build`. To use a different adapter, install it and update your `svelte.config.cjs` accordingly. The following official adapters are available:

- [@sveltejs/adapter-node](https://github.com/sveltejs/kit/tree/master/packages/adapter-node)
- [@sveltejs/adapter-static](https://github.com/sveltejs/kit/tree/master/packages/adapter-static)
- [@sveltejs/adapter-netlify](https://github.com/sveltejs/kit/tree/master/packages/adapter-netlify)
- ...more soon
