# 💋 millimetr-sass

This is a millimetr starting template with [Sass](https://sass-lang.com/) integration

_Note that the CSS selectors in this demo follow the [BEM convention](https://en.bem.info/methodology/css/#selectors). However you are welcome to restructure them according to your preferences._

## Getting started

1. `git clone https://github.com/millimetr/millimetr-default.git`
2. `npm install`
3. `npm start`

## Principles

- 📄 **HTML templates are written in [EJS](https://ejs.co/)**
- 🤖 **The `millimetr.config.js` file is central to this starter.**
- 👓 **No hidden behaviour, everything is documented via `millimetr.config.js` file.**
- 💋 **`src/scss/styles` automatically gets compiled into `src/static/assets/styles.css`**

## Example routes

This starting template starts with three routes:

- `/`: The basic landing-route.
- `/hardcoded`: Illustrates how hardcoded values can be passed to route templates.
- `/dynamic`: Illustrates how dynamically generated values can be passed to route templates.
- `/remote`: Illustrates how remote data can be fetched and passed to route templates.
