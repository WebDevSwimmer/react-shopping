## Simple ecommerce cart application

<p align="center">
  <img src="./doc/react-shopping-cart-min.gif">
</p>

## Basic Overview

This simple shopping cart prototype shows how React components and Redux can be used to build a
friendly user experience with instant visual updates and scaleable code in ecommerce applications.

#### Features

- Add and remove products from the floating cart
- Sort products by highest to lowest and lowest to highest price
- Filter products by available sizes
- Products persist in floating cart even after page reloads
- Responsive design for desktop, tablets and mobile
- Product stoppers for free shipping
- Unit tests, integration tests and e2e testing

#### Using

- React
  - Redux - state management
- Nodejs
  - Express CORS Middleware (Node and React run in different port)
  - Nodemon - for a better development experience
  - Concurrently - To run multiple tasks at once
- Axios - for promise HTTP requests
- CSS
  - BEM methodology
  - SASS
- Moxios - to stub http request
- Enzyme - to mount, shallow, render and query the DOM tree of React components
- Webdriverio - to do automated tests in a real browser environment
- Native local storage - to persist products in cart even after page reload

## Build/Run

#### Requirements

- Node.js
- NPM

```javascript

/* First, Install the needed packages */
npm install

/* Then start both Node and React */
npm start

/* To run the tests */
npm run test

/* Running e2e tests */
npm run wdio


```

## About tests

- Unit tests
  - All components have at least a basic smoke test
- Integration tests
  - Fetch product and add to cart properly
- e2e
  - Webdriverio - Add and remove product from cart

### Copyright and license

The MIT License (MIT). Please see License File for more information.
<p align="center"><img src="https://avatars3.githubusercontent.com/u/47307975?s=400&u=5d3a6ad302503c236b60f5d85a0e32d564898838&v=4" width="50" height="50"/></p>
<p align="center">
  <sub>A little project by <a href="https://github.com/zhangwei5479">Zhang Wei</a></sub>
</p>
</p>
