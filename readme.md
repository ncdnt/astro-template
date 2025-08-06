# Astro Starter Kit

```sh
pnpm create astro@latest -- --template ncdnt/astro-template
```

Basic Astro 5 project template with TS, ESLint, and Prettier set up out-of-the-box.

## 🚀 Project Structure

The project structure is similar to that of a default minimal Astro project, but
with the extra ESLint and Prettier config files.

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page
is exposed as a route based on its file name.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command            | Action                                      |
| :----------------- | :------------------------------------------ |
| `pnpm install`     | Installs dependencies                       |
| `pnpm dev`         | Starts local dev server at `localhost:4321` |
| `pnpm build`       | Builds your production site to `./dist/`    |
| `pnpm preview`     | Previews your build locally                 |
| `pnpm astro check` | Runs diagnostics + type-checking            |
| `pnpm fmt`         | Runs `prettier --check` on the project root |

## 👀 Learn more

Feel free to check [Astro's docs](https://docs.astro.build) to learn more.
