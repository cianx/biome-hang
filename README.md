# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


Steps to reproduce

```
yarn
yarn dlx @biomejs/biome init
yarn dlx @biomejs/biome check ./src
```
the check returns that it found 5 errors


if I run `yarn dlx @biomejs/biome check ./src --apply`, biome hangs

