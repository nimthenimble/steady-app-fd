---
title: "#1: Favicon Border-Radius Update"
subtitle: "Simple asset change on the index.html <head> section to modify the current favicon"
date: "2025-03-16"
toc: True
tags:
  - HTML
  - Favicon
  - Border-Radius
---

In [Steady's Website](https://steady.rocks) the favicon used is the official logo which can be found in the [assests folder](https://steady.rocks/assets/images/steady-logo.webp) along with other files.

But throughout the whole website the Steady logo is always modified to have a quite neat and in design terms very visual appealing image. In this case the favicon should be changed, replacing all favicon assets for the new image with the Steady logo with a border-radius.

```html
<!-- Favicon -->
 <link rel="apple-touch-icon" sizes="180x180" href="/assets/images/favicon/apple-touch-icon.png">
 <link rel="icon" type="image/png" sizes="32x32" href="/assets/images/favicon/favicon-32x32.png">
 <link rel="icon" type="image/png" sizes="16x16" href="/assets/images/favicon/favicon-16x16.png">
 <link rel="shortcut icon" href="/assets/images/favicon/favicon.ico">
```

This is the code of the favicons, the `href` needs to be updated to link to the new Steady logo.

**Signed: Hugo Urías | [LinkedIn](https://linkedin.com/in/vallecas)**