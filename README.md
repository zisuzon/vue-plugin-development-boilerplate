# vue-plugin-development-boilerplate

## Project setup
```
yarn install
```

### To run and test the Component
```
yarn dev
```

### To build the pulgin
```
yarn build
```

Change the default component name according to your component and update the name in other places

```
src/TheComponent.vue
```

### Publish to NPM

```
npm publish --access public
```

### Use published plugin 

Locally, in a component
```
import MyButton from '@zisuzon/v-testing-plugin'
```

Globally, in a "main.js"
```
import MyButton from '@zisuzon/v-testing-plugin'

Vue.component('MyButtonGlobal', MyButtonGlobal)
```
