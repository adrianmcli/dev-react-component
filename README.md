# dev-react-component
A minimalistic boilerplate for developing a react component as an NPM package.

# How to use

1. Clone this repo into a folder of your choice:

  ```
  git clone https://github.com/adrianmcli/dev-react-component.git my-new-component
  ```

2. Run `yarn` or `npm install` inside the directory that was just created.
3. Change the `name`, `version`, and `description` inside `package.json`.
4. Start developing your component inside `src/index.js`.
5. Run `npm publish` to publish your component.

# Warning

This boilerplate only uses `babel-cli` to compile your react components. Whoever uses your react component will still need an additional build step. UMD compilation may be added later or in a separate branch.
