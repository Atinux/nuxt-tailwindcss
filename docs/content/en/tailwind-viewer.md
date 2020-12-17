---
title: Tailwind Viewer
description: 'Visualize your Tailwind configuration with the viewer.'
position: 4
category: Guide
categoryPosition: 2
---

Nuxt Tailwind will expose a `/_tailwind/` route in development so you can quickly visualize your tailwind configuration with easy copy pasting, thanks to the awesome [tailwind-config-viewer](https://github.com/rogden/tailwind-config-viewer) package ✨

The viewer is available from the `v3.4.0` of `@nuxtjs/tailwindcss`.

<video poster="https://res.cloudinary.com/nuxt/video/upload/v1606994332/nuxt-tailwind-colors_qlio2t.jpg" loop playsinline controls>
  <source src="https://res.cloudinary.com/nuxt/video/upload/q_auto/v1606994332/nuxt-tailwind-colors_qlio2t.webm" type="video/webm" />
  <source src="https://res.cloudinary.com/nuxt/video/upload/q_auto/v1606994332/nuxt-tailwind-colors_qlio2t.mp4" type="video/mp4" />
  <source src="https://res.cloudinary.com/nuxt/video/upload/q_auto/v1606994332/nuxt-tailwind-colors_qlio2t.ogv" type="video/ogg" />
</video>

When enabled, you will see the Tailwind viewer url in your terminal:

<img src="/tailwind-viewer.png" width="530" height="246" style="margin: 0;" />

Checkout the [viewer option](/options#viewer) to disable the viewer in development.
