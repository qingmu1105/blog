# Astro Starter Kit: Blog

```sh
npm create astro@latest -- --template blog
```

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

Features:

- ✅ Minimal styling (make it your own!)
- ✅ 100/100 Lighthouse performance
- ✅ SEO-friendly with canonical URLs and Open Graph data
- ✅ Sitemap support
- ✅ RSS Feed support
- ✅ Markdown & MDX support

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── content/
│   ├── layouts/
│   └── pages/
├── astro.config.mjs
├── README.md
├── package.json
└── tsconfig.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

The `src/content/` directory contains "collections" of related Markdown and MDX documents. Use `getCollection()` to retrieve posts from `src/content/blog/`, and type-check your frontmatter using an optional schema. See [Astro's Content Collections docs](https://docs.astro.build/en/guides/content-collections/) to learn more.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Check out [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

## Credit

This theme is based off of the lovely [Bear Blog](https://github.com/HermanMartinus/bearblog/).

## Archive

Welcome to the official [Astro](https://astro.build/) blog starter template. This template serves as a lightweight, minimally-styled starting point for anyone looking to build a personal website, blog, or portfolio with Astro.

This template comes with a few integrations already configured in your `astro.config.mjs` file. You can customize your setup with [Astro Integrations](https://astro.build/integrations) to add tools like Tailwind, React, or Vue to your project.

Here are a few ideas on how to get started with the template:

- Edit this page in `src/pages/index.astro`
- Edit the site header items in `src/components/Header.astro`
- Add your name to the footer in `src/components/Footer.astro`
- Check out the included blog posts in `src/content/blog/`
- Customize the blog post page layout in `src/layouts/BlogPost.astro`

Have fun! If you get stuck, remember to [read the docs](https://docs.astro.build/) or [join us on Discord](https://astro.build/chat) to ask questions.

Looking for a blog template with a bit more personality? Check out [astro-blog-template](https://github.com/Charca/astro-blog-template) by [Maxi Ferreira](https://twitter.com/Charca).
          