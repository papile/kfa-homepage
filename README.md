## Installation
Install node.js [https://nodejs.org/en/](https://nodejs.org/en/)

Install the NPM dependencies and build the javascript once in development mode.

```bash
npm install
npm run webpack:dev
```

## Development

```bash
npm run server
```

Hugo will start its development server on [http://localhost:1313/](http://localhost:1313/)


## Production build

```bash
npm run build
```

This will run webpack to produce production javascript then Hugo will build
static pages and unused CSS will be removed with Purgecss. 

Deploy the contents of `public/` to S3 or another hosting service.
