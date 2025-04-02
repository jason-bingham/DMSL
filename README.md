## Step-by-Step, Adding new projects

1. Prep photos
   1. Make longest side 1920px for gallery photos, and the thumbnail 400wx300h.
   2. Name thumbnail "mainthumb\_[name]"
2. Navigate to /projetos.astro
   1. Copy <a>
      1. Update href
      2. Key:
         | Type | Abbr. | Identifier | Result | Example |
         | --- | --- | --- | --- | --- |
         | Apartmento | Ap | [NN] | Ap[NN] | ApMV |
         | Corporativa | Corp | [NN] | Corp[NN] | CorpPropz |
         | Empreendimento | Empr | [NN] | Empr[NN] | EmprVB |
         | Galpão | Gal | [NN] | Gal[NN] | GalJPF493 |
         | Residência | Res | [NN] | Res[NN] | ResHPS |
   2. Update <img> src to "/projetos/[name (see key above)]/mainthumb\_[name].jpg"
   3. Update title. Spell out type if space permits
   4. Find "projeto-profiles"
   5. Copy up first "projeto-profile"
   6. Update comment and id
   7. Update path to photos and number of photos
   8. Add or remove "contain" class as needed (on portrait or oddly shaped images)

# Astro Starter Kit: Minimal

```sh
npm create astro@latest -- --template minimal
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/minimal)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/minimal)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/minimal/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

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

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
