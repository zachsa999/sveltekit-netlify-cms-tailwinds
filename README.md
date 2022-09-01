# A plug and play Sveltekit template with NetlifyCMS, and MDsveX

<a href="https://app.netlify.com/start/deploy?repository=https://github.com/buhrmi/sveltekit-netlify-cms&amp;stack=cms"><img src="https://www.netlify.com/img/deploy/button.svg" alt="Deploy to Netlify"></a>

Visit [kit.svelte.dev](https://kit.svelte.dev) to read the SvelteKit docs.

Go to [netlifycms.org](https://www.netlifycms.org) to check out the static git based cms!

Integrates with [mdsvex.com](https://mdsvex.com) for powerful clean markdown. This is based on [mdx](https://mdxjs.com/docs/what-is-mdx/#mdx-syntax), view this site for the syntax.

## configure netlify

Go to your site in the Netlify Admin

Click identity in the sidebar

Click Enable Identity and invite whoever you want

Scroll down to External Providers and add a provider, for this app its GitHub, select default to hide github branding in the page

## create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
