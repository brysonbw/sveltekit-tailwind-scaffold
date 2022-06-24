# Sveltekit Tailwind Scaffold

A minimal typescript Sveltekit tailwind scaffold starter 

## Tree (sveltekit-scaffold/src)

```
src
 ┣ assets
 ┣ components
 ┃ ┗ Navbar.svelte
 ┣ routes
 ┃ ┣ api
 ┃ ┣ __error.svelte
 ┃ ┣ __layout.svelte
 ┃ ┗ index.svelte
 ┣ stores
 ┣ app.css
 ┣ app.d.ts
 ┗ app.html
```

## Usage

```bash
$ git clone git@github.com:brysonbw/sveltekit-tailwind-scaffold.git

$ cd sveltekit-tailwind-scaffold

$ rm -fr .git

$ npm install # or pnpm install or yarn install
```

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

## Updating Dependencies

Sveltekit is still in beta at the this current time. So to keep up-to-date check for updates (if I don't update package dependencies from time to time):

```bash
#  check if any (or, specific) installed packages are currently outdated -> output list of outdated dependencies or none if no update required
$ npm outdated

# update a specific package
$ npm update <package_name>

# update all dependencies
$ npm update
```

## Creating A Project With `npm init svelte@next` & `npx svelte-add@latest tailwindcss`

You can use this scaffold or create a sveltekit project this way. It's what I normally do and I just added the files and directories I usually start off with using **npm init svelte@next** & **npx svelte-add@latest tailwindcss** for this scaffold - either or is fine :)

```bash
$ npm init svelte@next

# add tailwind css
$ npx svelte-add@latest tailwindcss

$ npm install # or pnpm install or yarn install
```

You add other integrations to your svelte/sveltekit projects besides tailwind with `npx svelte-add`.

> [svelte-add](https://github.com/svelte-add/svelte-add)

