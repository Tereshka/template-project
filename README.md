# Template project [LIVE DEMO](https://tereshka.github.io/template-project/)
Used stack: React, Redux, TypeScript, Sass/Scss

Just a simple template. Has all required installations and setups. Prepared for deploying to github.<br/>
Folders:
- assets - for different images
- components - for project  components
- hooks - for custom hooks
- mock - for some template data used in components instead of loading from server
- store - redux store
- style - template with Colors, but can be some different styles used in all project's components
- types - for TS types, classes and so on
- utils - for some methods, that are needed for some needs

You can add any other folder, remove unnecessary ones, feel free.

>If you don't need deploying on GitHub, remove `homepage` property in `package.json`, so you application will starts from `http://localhost:3000/`, otherwise it will be `http://localhost:3000/app-name`

## Available Scripts

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm start

# build for production
$ npm run build

# build for deploy on github pages
$ npm run deploy
```