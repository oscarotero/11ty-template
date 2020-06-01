# Static site

Basic template to build static site with [11ty](https://www.11ty.dev/)

- Postcss
- ES5 modules (no babel or webpack)
- Prettier
- Automatic deploy to Github Pages 
  > Configure the PATH_PREFIX variable in .github/workflows/gh-pages.yml

```sh
npm install
npm start

npm run prettier  # Format the code
npm run build     # Build de site
```