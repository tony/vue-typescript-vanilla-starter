See also: https://github.com/tony/react-typescript-vanilla-starter

Split off of https://github.com/tony/cv v2 in the initial stages

MIT licensed. Feel free to copy and paste, fork, etc.

Summary
-------
Dev server, typed webpack config, typescript, jsx, babel.

No SASS/SCSS/LESS. No static files. Wiring those in are highly dependent on
integration.

Usage
-----

.. code-block:: bash
   
   npm install  # install packages

   npm run start  # launch + hot reloading + watch file changes http://localhost:3091

   npm run build  # build to dist/

Environmental variables
"""""""""""""""""""""""

`Webpack's environmental variables`_ can be passed (``--env``):

Launch dev server on port 3092:

``npm run start -- --env.devServerPort 3092``

``npm run start -- --env.production``

.. _Webpack's environmental variables: https://webpack.js.org/guides/environment-variables/

Contribution guidelines
-----------------------
Corrections: ✔️

Package updates: ✔️  (*please QA to verify build output / watch / reloading works*)

CI System: ✔️  (*get travis setup*)

New feature / Loader: 🚫 (*please create a fork!*)

Thanks
------
- https://github.com/microsoft/TypeScript-Vue-Starter/
- https://vue-loader.vuejs.org/guide/#manual-setup
