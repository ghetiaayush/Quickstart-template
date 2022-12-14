# Quickstart template

### following topics are covered in this demo 

- Initialize Vite app
- Setup Tailwind CSS
- Setup ESLint & Prettier
- Setup Vue Router
- Setup Vuex
- Styling
- Vuex usage example
- Vue router usage example
 
### following Installation commands are used in these demo

## Create Vite App
npm init @vitejs/app project-name

## Install Tailwind + dependencies
npm install -D tailwindcss@latest postcss@latest autoprefixer@latest

## Install ESLint + Prettier
npm install --save-dev eslint prettier eslint-plugin-vue eslint-config-prettier

## Install Vue Router
npm install vue-router@4

## Install Vuex
npm install vuex@next --save

## put the below code in the mention file at the root of your document 
1) .eslintrc.js:
module.exports = {
extends: [
  'plugin:vue/vue3-essential',
  'prettier',
],
rules: {
  // override/add rules settings here, such as:
  'vue/no-unused-vars': 'error',
},
}

2) .prettierrc.js:
module.exports = {
    semi: false,
    tabWidth: 4,
    useTabs: false,
    printWidth: 80,
    endOfLine: 'auto',
    singleQuote: true,
    trailingComma: 'es5',
    bracketSpacing: true,
    arrowParens: 'always',
 }
 
 - NOTE:-
After cloning the above repository, go to the project folder and install node modules `npm install`  This is essentially a fresh install of Vue 3 + Vite, ESLint, Prettier, TailwindCSS, Vue Router & Vuex.
