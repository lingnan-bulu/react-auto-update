
## Before
in component
```js

class xxxx extends React.Component {
  ...
  shouldComponentUpdate(){
    if(...){
      return true or false
    }
  }
}
```

## After
Component only with local imports
```js
import reactAutoUpdate from 'react-auto-update'
@reactAutoUpdate
class xxxx extends React.Component {
  ...
}
```

## Installation 
1. Install
```npm install react-auto-update --save```

2. Add react-auto-update in component top:
```js
@reactAutoUpdate

but this package depend on immutable.js
Done!
