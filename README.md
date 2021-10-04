# Vite Vue Quickstart
> Starter template for a Vue project using Vite as a build tool


## Resources

- [Vite](https://michaelcurrin.github.io/dev-resources/resources/javascript/packages/vite/)
- [Vue](https://michaelcurrin.github.io/dev-resources/resources/javascript/packages/vue/)
- [TypeScript](https://michaelcurrin.github.io/dev-resources/resources/typescript/)


## Related projects

- [vite-react-quickstart](https://github.com/MichaelCurrin/vite-react-quickstart)


## Notes

### Templates

The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

### Type support for .vue files

Since TypeScript cannot handle type information for `.vue` imports, they are shimmed to be a generic Vue component type by default. In most cases this is fine if you don't really care about component prop types outside of templates.

However, if you wish to get actual prop types in `.vue` imports (for example to get props validation when using manual `h(...)` calls), you can enable Volar's `.vue` type support plugin by running `Volar: Switch TS Plugin on/off` from VS Code command palette. If you have the Volar extension installed in VS Code.
