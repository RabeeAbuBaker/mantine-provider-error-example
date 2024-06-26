# mantine-provider-error-example

This repo was created to reproduce an error with MantineProvider& Remix

- [vite-component-library-template](https://github.com/IgnacioNMiranda/vite-component-library-template) - Was used as a template for a component library
- [remix-template](https://github.com/mantinedev/remix-template) - Was used for Mantine w/ Remix

vite-component-library-template is simply [exporting](https://github.com/RabeeAbuBaker/mantine-provider-error-example/blob/main/vite-component-library-template/src/lib/index.ts#L3) MantineButton and remix-template is importing and then [using](https://github.com/RabeeAbuBaker/mantine-provider-error-example/blob/main/remix-template/app/components/Welcome/Welcome.tsx#L8) it. 

To run the project: 
- Run `pnpm i` on vite-component-library-template
- Run `pnpm run build:lib` on vite-component-library-template
- Run `pnpm i` on remix-template 
- Run `pnpm run dev` on remix-template

If you make changes in the component library, for them to take effect, you have to run `pnpm run build:lib` again on the vite-component-library-template and then `pnpm i` on the remix-template directory.

Error after running the Remix app:

<img width="1481" alt="image" src="https://github.com/RabeeAbuBaker/mantine-provider-error-example/assets/38038348/c8ea1e12-388f-40b0-8324-ae522bcc9db2">
