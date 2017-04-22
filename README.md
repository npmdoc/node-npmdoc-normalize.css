# npmdoc-normalize.css

#### api documentation for  [normalize.css (v6.0.0)](https://necolas.github.io/normalize.css)  [![npm package](https://img.shields.io/npm/v/npmdoc-normalize.css.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-normalize.css) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-normalize.css.svg)](https://travis-ci.org/npmdoc/node-npmdoc-normalize.css)

#### A modern alternative to CSS resets

[![NPM](https://nodei.co/npm/normalize.css.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/normalize.css)

- [https://npmdoc.github.io/node-npmdoc-normalize.css/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-normalize.css/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-normalize.css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-normalize.css/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-normalize.css/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-normalize.css/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "normalize.css",
    "version": "6.0.0",
    "description": "A modern alternative to CSS resets",
    "main": "normalize.css",
    "style": "normalize.css",
    "files": [
        "LICENSE.md",
        "normalize.css"
    ],
    "devDependencies": {
        "stylelint": "^7.9.0",
        "stylelint-config-standard": "^16.0.0"
    },
    "scripts": {
        "test": "stylelint normalize.css"
    },
    "repository": "necolas/normalize.css",
    "contributors": [
        "Jonathan Neal <jonathantneal@hotmail.com> (http://jonathantneal.com/)",
        "Nicolas Gallagher <nicolas@nicolasgallagher.com> (http://nicolasgallagher.com/)"
    ],
    "license": "MIT",
    "bugs": "https://github.com/necolas/normalize.css/issues",
    "homepage": "https://necolas.github.io/normalize.css",
    "stylelint": {
        "extends": "stylelint-config-standard",
        "rules": {
            "font-family-no-duplicate-names": [
                true,
                {
                    "ignoreFontFamilyNames": [
                        "monospace"
                    ]
                }
            ]
        }
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
