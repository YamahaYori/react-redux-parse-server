# React Redux Parse Server

- Server side rendering with [ExpressJS](http://expressjs.com/)
- Routing with the standard [React Router](https://github.com/reactjs/react-router)
- [Redux](https://github.com/reactjs/redux) for state management
  - Debugging with [Redux DevTools](https://github.com/gaearon/redux-devtools) and [redux-logger](https://github.com/fcomb/redux-logger) middleware
  - [Redux Form](https://github.com/erikras/redux-form) for handling form state
- API/Auth with [ParseServer](https://github.com/ParsePlatform/parse-server)
- [Radium](https://github.com/FormidableLabs/radium) for inline styles (might be removed soon)
- Linting with [ESLint](http://eslint.org/)
- All transformed with [Babel](babeljs.io)

## Initializing

Install dependencies:
```bash
npm install
```

Run server and Parse:
```bash
npm start
```

Open another terminal and run:
```bash
npm run watch-client
```
...to run Webpack to bundle files into `main.js`:

## Environment variables

Parse has designated [environment variables](https://github.com/ParsePlatform/parse-server#using-environment-variables) you can use.


# Disclaimer
 There are still a lot of things to tweak on this, so don't expect it to be 100% there just yet. If you have contributions, I'd be happy to check out a pull request. :zap: