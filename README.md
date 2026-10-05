# Base & Beyond — 5D Immersive Agency Site

A luxury, motion-first, WebGL-driven agency website for Base & Beyond.

## Local development

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
```

Upload/deploy the generated `dist/` directory to the public web root.

## cPanel Git deployment

The repository is Vite-based. Your cPanel deployment step must run:

```bash
npm ci
npm run build
```

Then publish/copy the contents of `dist/` into the domain's document root.

## Stack

React, Vite, Three.js / React Three Fiber, Drei, GSAP ScrollTrigger, Motion and Lenis.

The visual interaction language is custom-built using established web technologies including React, Three.js, GSAP, WebGL, Vite and Lenis.
