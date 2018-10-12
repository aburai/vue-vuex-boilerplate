# vue-vuex-boilerplate

Vue 2, Vuex, Webpack 3 and Typescript 2 starter boilerplate.

## Usage
```
$ npm install -g vue-cli
$ vue init bamboo-c/vue-vuex-boilerplate my-project
$ cd my-project
$ yarn install
$ yarn run dev
```

## Used

- Vue 2
- Vuex
- vue-router
- Webpack 3
- TypeScript 3
- karma
- sass

## File stlucture

```
template
│   karma configs
│   package.json
│   README.md
│   tsconfig.json
│   webpack.config.json // import config/
│   yarn.lock
│
└───config
│       // webpack settings
│       ...
│
└───environment
│       dev.env.js
│       prod.env.js
│
└───node_modules
│       // nodo modules
│       ...
│
└───static
│       favicon.ico
│
└───src
    │   index.html
    │   main.ts
    │   test.ts
    │
    └───api
    │      api mock data
    └───assets
    │   └───images
    │          // project images
    │          ...
    │
    └───components
    │   └───container
    │   │      // container
    │   │      ...
    │   │
    │   └───modules
    │   │      // modules
    │   │      ...
    │   │
    │   └───ui
    │          // ui
    │          ...
    └───router
    │     index.ts
    │
    └───store
    │     index.ts
    │     actions.ts
    │     getters.ts
    │     mutation-types.ts
    │     mutation.ts
    │     state.ts
    │
    └───styles
    │   │   main.scss
    │   │
    │   └───common
    │   │      // common styles
    │   │      ...
    │   │
    │   └───components
    │   │      └───container
    │   │      │      // containers styles
    │   │      │      ...
    │   │      │
    │   │      └───modules
    │   │      │      // modules styles
    │   │      │      ...
    │   │      │
    │   │      └───ui
    │   │             // ui styles
    │   │             ...
    │   │
    │   └───foundation
    │          _normalize.scss
    │   
    └───utils
            component-test.ts
            log.ts

```
