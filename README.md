# Reproduction for `storyblok-nuxt` issue #688
1. Clone this repository and open it on VSCode
2. Make sure you have the official Vue and the builtin Typescript extensions.
3. Run `npm install` to install the dependencies
4. Run `npm run dev` to start the development server
5. Open `app.vue` and see how the type for the `MyComponent` component is not being recognized as `unknown`
6. Remove the Storyblok module from `nuxt.config.ts`
7. Now, the type for the `MyComponent` component is recognized correctly and the editor is showing an error for missing props.
8. Updating the Nuxt version to 3.11.2 fixes the issue