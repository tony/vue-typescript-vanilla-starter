See also: <https://github.com/tony/react-typescript-vanilla-starter>

Split off of <https://github.com/tony/cv> v2 in the initial stages

MIT licensed. Feel free to copy, fork, etc.

# Summary

Dev server, typed webpack config, typescript, jsx, babel.

No SASS/SCSS/LESS. No static files. Wiring those in are highly dependent on integration.

# Usage

```bash
npm install  # install packages

npm run start  # launch + hot reloading + watch file changes http://localhost:3091

npm run build  # build to dist/
```

## Environmental variables

[Webpack's environmental variables] can be passed (`--env`):

Launch dev server on port 3092:

`npm run start -- --env.devServerPort 3092`

`npm run start -- --env.production`

`npm run start -- --open` Launch browser + build + watch files, <http://localhost:3099>

[webpack's environmental variables]: https://webpack.js.org/guides/environment-variables/

# Contribution guidelines

Corrections: ✔️

Package updates: ✔️ (_please QA to verify build output / watch / reloading works_)

CI System: ✔️ (_get travis setup_)

New feature / Loader: 🚫 (_please create a fork!_)

# Thanks / Credits

- <https://github.com/microsoft/TypeScript-Vue-Starter/> (reference, tsconfig.json and placeholder
  Vue components only this starter is _not derived_ from it)
- <https://vue-loader.vuejs.org/guide/#manual-setup>
