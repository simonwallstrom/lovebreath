## Project Overview 

- The project uses [Eleventy](https://11ty.io) as a static site generator
- Default templating is [Nunjucks](https://mozilla.github.io/nunjucks/) (can be changed if you want)
- PostCSS set up to handle:
	- TailwindCSS
	- Autoprefixer 
- PurgeCSS to remove unused CSS (set up for TailwindCSS by default) in production
- HTML minified in production
- CSS inlined and minified in production
- Webpack used to bundle scripts
- Scripts optimised for production
- Document `<head>` crafted using [htmlhead.dev](https://htmlhead.dev)

---

## Getting Started

### Install dependencies

```
npm install
```

### Working locally
Starts watch tasks to compile when changes detected

```
npm start
```

### Creating a production build 
Minify HTML, compress JS, inline and minify CSS.

``` 
npm run build
```

---

## Deployment 

You can host the production output on any web server or service you like and upload it via any method, it'll work. 

If you don't have an existing place to host your site you should have a look at [Netlify](https://www.netlify.com), I can't recommend it enough. To get started you can hit the button below.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/simonwallstrom/lovebreath)