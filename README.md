# mantine-provider-error-example

This repo was created to reproduce an error with MantineProvider& Remix

- [vite-component-library-template](https://github.com/IgnacioNMiranda/vite-component-library-template) - Was used as a template for a component library
- [remix-template](https://github.com/mantinedev/remix-template) - Was used for Mantine w/ Remix

vite-component-library-template is simply exporting MantineButton and remix-template is importing and then using it. 

To run the project run `pnpm i` on both directories (vite-component-library-template first) and then "pnpm run dev" on the remix-template directory.

After making changes, run `pnpm run build:lib` on the vite-component-library-template and then `pnpm i` on the remix-template directory.
