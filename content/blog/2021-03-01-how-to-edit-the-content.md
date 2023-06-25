---
createdAt: 2021-03-01
title: Add PWA In Nuxt JS
description: Add PWA In Nuxt JS - Ahmed Waleed senior frontend developer
---
## Installation

Add `@nuxtjs/pwa` dependency to your project:

```javascript
// With Yarn
yarn add --dev @nuxtjs/pwa

// With NPM
npm i --save-dev @nuxtjs/pwa
```

Edit your `nuxt.config.js` file to add pwa module::

```javascript
// nuxt.config.js
{
  buildModules: [
    '@nuxtjs/pwa',
  ]
}
```

**NOTE:** If using `ssr: false` with production mode without `nuxt generate`, you have to use `modules` instead of `buildModules`

## Configuration

```javascript
// nuxt.config.js
{
  pwa: {
    icon: false // disables the icon module
  }
}
```

## \-﻿ Useful Links -

### <https://pwa.nuxtjs.org/>