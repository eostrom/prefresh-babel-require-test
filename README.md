# Test case for preactjs/prefresh#444

`index.mjs` imports `@prefresh/babel-plugin`, while `index.js` requires it.
            
After running `yarn install`, `node index.mjs` prints the imported function. 
                                              
`node index.js` fails with an error:

> Error: Cannot find module '/Users/eostrom/workspace/swagleft/prefresh-babel-require-test/node_modules/@prefresh/babel-plugin/dist/src/index.js'
