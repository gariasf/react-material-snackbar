# react-material-snackbar-custom-classname [![Build Status](https://travis-ci.org/gariasf/react-material-snackbar-custom-classname.svg?branch=master)](https://travis-ci.org/gariasf/react-material-snackbar-custom-classname)

*A material design snackbar react component (2KB gzipped)*

> Created using [react-material-snackbar-custom-classname](https://github.com/gariasf/react-material-snackbar-custom-classname/)

### [Demo](https://gariasf.github.io/react-material-snackbar-custom-classname/)

### Installation

```sh
npm install --save react-material-snackbar-custom-classname
```
or 

```sh
yarn add react-material-snackbar-custom-classname
```

### Usage

```js
import SnackBar from 'react-material-snackbar-custom-classname';

<SnackBar
  show={true}                            //Boolean  - Required and Default - `false`
  timer={6000}                           //Number   - Optional and Default - `4000` (4 secs)
  customClass={...}                      //String   - Optional
>
  // Pass any HTML element to render
  <p>Loading...</p>
</SnackBar>
```

## License

Original package MIT © [Gokulakrishnan Kalaikovan](https://github.com/gokulkrishh)
Thi version MIT [Guillem Arias](https://github.com/gariasf)