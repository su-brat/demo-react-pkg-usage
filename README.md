# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Using a react npm package
- Use `npm install package-name` same as any other npm package installation
- Import the component or hook as exported from the package
- If there is css bundle in the package, to see the css changes add the `link` tag with path to the css file in `node_modules` to the `html` container file (Refer `index.html`)