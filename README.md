# Vue WebApp Seed

> Vue WebApp Seed Project

[![CircleCI](https://circleci.com/gh/ijse/vue-webapp-seed.svg?style=svg)](https://circleci.com/gh/ijse/vue-webapp-seed)

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification, result in `dist/`
npm run build

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

## Docs you should read

- StandardJS (http://standardjs.org)
- Vue 2.0 (http://rc.vuejs.org/guide/)
- Vuex 2.0 (http://vuex.vuejs.org/en/index.html)
- Vue-router 2.0 (http://router.vuejs.org/en/index.html)
- Turret (http://turretcss.com/docs/getting-started/)
- Vue-resource (https://github.com/vuejs/vue-resource/tree/master/docs)
- Vue-i18n (https://kazupon.github.io/vue-i18n/)
- Vue-loader (http://vuejs.github.io/vue-loader)
- Nightwatch (http://nightwatchjs.org/guide)
- Karma (https://karma-runner.github.io/1.0/intro/configuration.html)
- Mocha (https://mochajs.org/)
- Webpack (http://vuejs-templates.github.io/webpack/)

## Source Directory

- src/
  - assets/ : resources that will be compiled by webpack
  - components/ : these have nothing to do with business logic
  - i18n/ : the locales settings
  - modules/ : business modules
  - vuex/ : data state management
  - App.vue : the application instance
  - main.js : start entry
  - routes.js : app routes definations


## Publish Steps


## i18n resource

Get the default language from `navigator.language`. The fallback language is 'en'.

### i18n file Formatting
https://kazupon.github.io/vue-i18n/formatting.html

### Language name List
```
navigator.languages = ["af", "sq", "ar-SA", "ar-IQ", "ar-EG", "ar-LY", "ar-DZ", "ar-MA", "ar-TN", "ar-OM",
 "ar-YE", "ar-SY", "ar-JO", "ar-LB", "ar-KW", "ar-AE", "ar-BH", "ar-QA", "eu", "bg",
 "be", "ca", "zh-TW", "zh-CN", "zh-HK", "zh-SG", "hr", "cs", "da", "nl", "nl-BE", "en",
 "en-US", "en-EG", "en-AU", "en-GB", "en-CA", "en-NZ", "en-IE", "en-ZA", "en-JM",
 "en-BZ", "en-TT", "et", "fo", "fa", "fi", "fr", "fr-BE", "fr-CA", "fr-CH", "fr-LU",
 "gd", "gd-IE", "de", "de-CH", "de-AT", "de-LU", "de-LI", "el", "he", "hi", "hu",
 "is", "id", "it", "it-CH", "ja", "ko", "lv", "lt", "mk", "mt", "no", "pl",
 "pt-BR", "pt", "rm", "ro", "ro-MO", "ru", "ru-MI", "sz", "sr", "sk", "sl", "sb",
 "es", "es-AR", "es-GT", "es-CR", "es-PA", "es-DO", "es-MX", "es-VE", "es-CO",
 "es-PE", "es-EC", "es-CL", "es-UY", "es-PY", "es-BO", "es-SV", "es-HN", "es-NI",
 "es-PR", "sx", "sv", "sv-FI", "th", "ts", "tn", "tr", "uk", "ur", "ve", "vi", "xh",
 "ji", "zu"];
```


