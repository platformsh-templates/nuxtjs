> [!WARNING]
> **This repository is no longer maintained by our internal teams.**  
> The template is provided *as is* and will not receive updates, bug fixes, or new features.  
> You are welcome to contribute on it or fork the repository and modify it for your own use.
> To deploy this template on [Upsun](https://www.upsun.com), you can use the [ConvSun](https://github.com/upsun/convsun)
> tool to convert an existing `.platform.app.yaml` configuration file to the [Upsun Flex format](https://docs.upsun.com/create-apps/app-reference/single-runtime-image.html).

# NuxtJS for Platform.sh

This template builds a simple application using the NuxtJS web framework that can be used a starting point.

NuxtJS is an open-source web framework based on Vue.js.

## Features

* Node.js 18
* Automatic TLS certificates
* yarn-based build

## Customizations

The following files and additions make the framework work on Platform.sh, modified from the [`npx nuxi init <app>`](https://nuxt.new/) command for Nuxt v3.
If using this project as a reference for your own existing project, replicate the changes below to your project.

* The `.platform.app.yaml`, `.platform/services.yaml`, and `.platform/routes.yaml` files have been added. These provide Platform.sh-specific configuration and are present in all projects on Platform.sh. You may customize them as you see fit.

## References

* [NuxtJS](https://nuxtjs.org/)
* [Node.js on Platform.sh](https://docs.platform.sh/languages/nodejs.html)
