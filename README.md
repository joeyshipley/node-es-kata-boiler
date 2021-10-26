# ES Kata Boiler

### Local Setup
- Node 16.x installed (consider nvm if you have not used it before)
- ``` terminal > npm install ```

#### Running the kata
- ``` terminal > npm start ```

#### Running the test suite
- ``` terminal > npm test ```

#### Running an individual specs/tests
If not already installed, you will need to have mocha installed globally to your node version.
- ``` terminal > npm install --global mocha ```

##### Specific spec file
- ``` terminal > mocha tests/kata.specs.js```

##### Specific test
- ``` terminal > mocha -g 'allows tests to control dependency output' ```

*Replace the string value with the message in your test declaration.*

### Resources
- [nvm](https://github.com/nvm-sh/nvm)
- [Mocha](https://mochajs.org/)
- [Chai](https://www.chaijs.com/)
