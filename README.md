# Shopify Webpack Theme Development Tool

## System Requirements
- [Node](https://nodejs.org/en/) (v10.16.3+)
- [NPM](https://docs.npmjs.com/try-the-latest-stable-version-of-npm) (5+)
- [Theme Kit](https://shopify.github.io/themekit/)

## Getting Started
- Download this repo as a zip, and run `npm install` from the root directory. 
- Update `example.config.yml` with private app password, theme ID, and store .myshopify.com domain
- Rename `example.config.yml` to `config.yml`
- Run `npm run deploy` to build theme in production mode and deploy to target theme from config.yml
  - this is destructive.
- Run `npm start` to begin watching files and pushing updates