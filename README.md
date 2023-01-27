# Sweet Suite Nuxt Base
Base Nuxt app to be extended through [layers](https://nuxt.com/docs/guide/going-further/layers).

## Issues
- When using this layer, it's important to also install these packages: `@nuxtjs/tailwindcss @vueuse/nuxt` (this is hopefully temporariy, see workaround below)
> Currently, with git remote sources, if a layer has npm dependencies, you will need to manually install them in the target project. We are working on this to auto-install layer dependencies with git sources.
