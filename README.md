# Diff logger between states for redux

![logger](http://i.imgur.com/SR5jsdm.png?1)

### This is a fork

I've replaced `deep-diff` with `jsondiffpatch`

### WIP
**Don't be released until solved array's issue [#1](https://github.com/fcomb/redux-diff-logger/issues/1)**. Help appreciated!

### Install
`npm i --save redux-diff-logger`

### Usage
```
import logger from 'redux-diff-logger';

const createStoreWithMiddleware = applyMiddleware(logger)(createStore);
const store = createStoreWithMiddleware(reducer);
```

### License
MIT
