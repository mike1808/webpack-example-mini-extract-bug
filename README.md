# Mini CSS Extract Plugin Bug

Cannot use extract for both css and scss


```
Hash: 59c22bb51c79f33f2b5e
Version: webpack 4.1.0
Time: 516ms
Built at: 2018-3-6 12:23:23
 2 assets
Entrypoint main = main.css main.5e025217ef78681389a6.js
   [1] ./example.scss 39 bytes {0} [built]
   [2] ./example.css 157 bytes {0} [built] [failed] [1 error]
   [3] ./example.js 49 bytes {0} [built]
    + 1 hidden module

ERROR in ./example.css
Module parse failed: Unexpected token (1:3)
You may need an appropriate loader to handle this file type.
| h2 {
|     color: red;
| }
 @ ./example.js 1:0-23
Child mini-css-extract-plugin node_modules/mini-css-extract-plugin/dist node_modules/css-loader/index.js??ref--4-1!node_modules/sass-loader/lib/loader.js!example.scss:
    Entrypoint mini-css-extract-plugin = *
       [1] ./node_modules/css-loader??ref--4-1!./node_modules/sass-loader/lib/loader.js!./example.scss 183 bytes {0} [built]
        + 1 hidden module

```
