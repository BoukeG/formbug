# steps taken

## downloaded svelte:

```
npm create svelte@latest formbug
npm install
```

Used Barebone, TypeScript, pretty and vite

## Installed skeleton:

```
npm i @brainandbones/skeleton --save-dev
```

## Installed tailwindcss:

```
npx svelte-add@latest tailwindcss
npm install
```

## Changed files using:

[https://www.skeleton.dev/guides/tailwind]
[https://www.skeleton.dev/guides/styling]
[https://www.skeleton.dev/guides/themes]
[https://www.skeleton.dev/guides/frameworks/sveltekit]

Just the bares were changed to use Skeleton (works looking at the button), but not the form itself.

Then run:

```
npm run dev -- --open
```

Error: formbug/node_modules/@brainandbones/skeleton/styles/forms.css:43:2: The `bg-surface-200-700-token` class does not exist. If `bg-surface-200-700-token` is a custom class, make sure it is defined within a `@layer` directive.
