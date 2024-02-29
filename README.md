# Vite Tailwind SCSS AlpineJs boilerplate

Ready-to-use boilerplate for creating landing pages built on top of Vite, Tailwind, SCSS, and Alpine.

### start
```sh
git clone this_repository
cd this_directory
npm i
npm start
```

### build
```sh
npm run build
```

then grab everything from the dist folder

### change server port
Just change the port number in `vite.config.js` file
```javascript
export default {
    ...
    server: {
        port: 5140, // change this to your desired port
    }
    ...
}

```

### configure tailwind
There is a `tailwind.config.js` file with `purge` instructions and extra colors, feel free to customize it according to your need
