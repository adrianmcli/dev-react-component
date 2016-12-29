# dev-react-component
A minimalistic boilerplate for publishing a React component to NPM:

- No Babel
- No Webpack
- No testing
- No linting

You get to decide how to bring those in yourself if you decide that you need it. All this boilerplate does is get you developing and publishing as fast as possible.

# How to use

1. Clone this repo into a folder of your choice and `cd` into it:

  ```
  git clone https://github.com/adrianmcli/dev-react-component.git my-new-component
  cd my-new-component
  ```

2. Delete the existing git history by running `rm -rf .git` and then run `git init` to start fresh.
3. Run `yarn` or `npm install` to install the dependencies.
4. Change the `name`, `version`, and `description` inside `package.json`.
5. Start developing your component inside `src/MyComponent.js`.
6. Run `npm publish` to publish your component.

# Warning

This boilerplate makes use of [React Build Lib](https://github.com/adrianmcli/react-build-lib) and [React Build Dist](https://github.com/adrianmcli/react-build-dist) in order to generate the `lib` and `dist` folders for distribution. These two tools generate CommonJS and UMD modules respectively. Use of Babel and Webpack is hidden under the hood so that you can concentrate on sharing your component.
