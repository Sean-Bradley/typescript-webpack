# Typescript Webpack

TypeScript and Webpack Starter Boilerplate

To install
```bash
git clone https://github.com/Sean-Bradley/typescript-webpack.git
cd typescript-webpack
npm install -g typescript
npm install
```

To run using the inbuilt development server with hot module reloading (HMR) then,

```bash
npm run dev
```

Visit http://127.0.0.1:8080/

Any changes you make to the `./src/client/*.ts` will be recompiled and the browser automatically refreshed with the latest changes.



To build the the final production `bundle.js` then run
```
npm run build
```

> **Note**
    When running in dev mode, the final `bundle.js` is not built and placed into the `./dist/client/` folder but is served directly from the dev servers memory. The development mode provides extra functions not needed in the production mode version of the final `bundle.js`.
    The production version of `bundle.js` is compressed and does not contain any HMR or other development web server functionality.


