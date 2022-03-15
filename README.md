# Example

[https://github.com/NoahZinsmeister/web3-react](https://github.com/NoahZinsmeister/web3-react/tree/v6)  
v6 branch.

`git clone https://github.com/NoahZinsmeister/web3-react.git`  
`git branch v6`  
`git checkout v6`  
copy `example`

## Local Development

Before starting, ensure you've completed the instructions in the top-level [README.md](../README.md#local-development).

- Install dependencies\
  `yarn`

- Ensure that you've [`yarn link`ed](https://classic.yarnpkg.com/en/docs/cli/link/) all `@web3-react/*` packages, as well as `react` and `react-dom`, from `../packages/*` and `../node_modules/{react,react-dom}` respectively. This will ensure that changes you make to individual packages will be reflected immediately in the example (as long as you're running `yarn start` in the root).

- Serve the example on localhost\
  `yarn start`
