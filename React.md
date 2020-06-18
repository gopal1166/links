# Date: 18-06-2020: images in public folder

[link](https://stackoverflow.com/questions/50729967/src-images-folder-in-create-react-app)

```
import React, { Component } from 'react';

const iconPath = process.env.PUBLIC_URL + '/assets/icons/';

export default class TestComponent extends Component {
    constructor(props) {
        super(props);
    }
    render(){
    return (<img
        src={`${iconPath}icon-arrow.svg`}
        alt="more"
    />)
    }
}
```

# Semantic-ui-react using:
  https://medium.com/@a.carreras.c/using-semantic-ui-react-your-react-js-app-523ddc9abeb3
  
  index.html:
  CDN:
  <link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.3.1/semantic.min.css"></link>
  
  index.js:
  $ npm i semantic-ui --save

# Enzyme testing library cheetsheet:
   https://devhints.io/enzyme
