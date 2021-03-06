---
title: Configuration
description: The Nuxt.js default configuration covers most of usages. However, the nuxt.config.js file lets you overwrite it.
---

> The Nuxt.js default configuration covers most of usages. However, the nuxt.config.js file lets you overwrite it.

### build

This option lets you add modules inside the vendor.bundle.js file generated to reduce the size of the app bundle. It's really useful when using external modules

[Documentation about build integration](/api/configuration-build)

### cache

This option lets you enable cached components for better render performances.

[Documentation about cache integration](/api/configuration-cache)

### css

This option lets you define the CSS files/modules/libraries you want to set as globals (included in every pages).

[Documentation about css integration](/api/configuration-css)

### env

This option lets you define environment variables available both client and server side.

[Documentation about env integration](/api/configuration-env)

### generate

This option lets you to define each params value for every dynamic routes in your application that Nuxt.js transforms into HTML files.

[Documentation about generate integration](/api/configuration-generate)

### head

This option lets you to define all the defaults metas for your application.

[Documentation about head integration](/api/configuration-head)

### loading

This option lets you to customize the loading component load by default with Nuxt.js.

[Documentation about loading integration](/api/configuration-loading)

### plugins

This option lets you to define Javascript plugins to be ran before instantiating the root vue.js application.

[Documentation about plugins integration](/api/configuration-plugins)

### router

This option lets you to overwrite the default Nuxt.js configuration of vue-router.

[Documentation about router integration](/api/configuration-router)
