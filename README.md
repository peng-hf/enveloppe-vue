# Enveloppe Vue

An interactive 3D envelope animation built with Vue.js and GreenSock (GSAP). Click (or tap) the envelope to open it and reveal a letter inside — then click again to seal it back.

**[Live demo](http://enveloppe-vue.lyfing.dev)**

## Tech stack

- [Vue.js 2](https://v2.vuejs.org/) — component framework
- [GSAP 2 (GreenSock)](https://greensock.com/gsap/) — animation timeline
- CSS 3D transforms — envelope flip and flap mechanics
- SCSS — styles

## Getting started

Requires **Node 14**. If you use nvm:

```bash
nvm use
```

Then install and start:

```bash
npm install
npm run serve
```

Then open `http://localhost:8080` in your browser.

### Other commands

```bash
npm run build   # production build → dist/
npm run lint    # lint with ESLint
```

## Browser support

Tested on Chrome only. CSS `preserve-3d` and nested 3D transforms may behave differently in other browsers.
