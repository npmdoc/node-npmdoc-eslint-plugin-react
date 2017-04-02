# api documentation for  [eslint-plugin-react (v6.10.3)](https://github.com/yannickcr/eslint-plugin-react)  [![npm package](https://img.shields.io/npm/v/npmdoc-eslint-plugin-react.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-eslint-plugin-react) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-eslint-plugin-react.svg)](https://travis-ci.org/npmdoc/node-npmdoc-eslint-plugin-react)
#### React specific linting rules for ESLint

[![NPM](https://nodei.co/npm/eslint-plugin-react.png?downloads=true)](https://www.npmjs.com/package/eslint-plugin-react)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-plugin-react/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-eslint-plugin-react_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-plugin-react/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-eslint-plugin-react/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Yannick Croissant",
        "email": "yannick.croissant+npm@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/yannickcr/eslint-plugin-react/issues"
    },
    "dependencies": {
        "array.prototype.find": "^2.0.1",
        "doctrine": "^1.2.2",
        "has": "^1.0.1",
        "jsx-ast-utils": "^1.3.4",
        "object.assign": "^4.0.4"
    },
    "description": "React specific linting rules for ESLint",
    "devDependencies": {
        "babel-eslint": "7.1.1",
        "coveralls": "2.11.15",
        "eslint": "^2.0.0 || ^3.0.0",
        "istanbul": "0.4.5",
        "mocha": "3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "c5435beb06774e12c7db2f6abaddcbf900cd3f78",
        "tarball": "https://registry.npmjs.org/eslint-plugin-react/-/eslint-plugin-react-6.10.3.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "files": [
        "LICENSE",
        "README.md",
        "index.js",
        "lib"
    ],
    "gitHead": "b9cfdd6fccedd8c3ad1d2db334574bba38a1aaf8",
    "homepage": "https://github.com/yannickcr/eslint-plugin-react",
    "keywords": [
        "eslint",
        "eslint-plugin",
        "eslintplugin",
        "react"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "yannickcr",
            "email": "yannick.croissant+npm@gmail.com"
        }
    ],
    "name": "eslint-plugin-react",
    "optionalDependencies": {},
    "peerDependencies": {
        "eslint": "^2.0.0 || ^3.0.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yannickcr/eslint-plugin-react.git"
    },
    "scripts": {
        "coveralls": "cat ./reports/coverage/lcov.info | coveralls",
        "lint": "eslint ./",
        "test": "npm run lint && npm run unit-test",
        "unit-test": "istanbul cover --dir reports/coverage node_modules/mocha/bin/_mocha tests/**/*.js -- --reporter dot --opts tests/mocha.opts"
    },
    "version": "6.10.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module eslint-plugin-react](#apidoc.module.eslint-plugin-react)
1.  object <span class="apidocSignatureSpan">eslint-plugin-react.</span>configs
1.  object <span class="apidocSignatureSpan">eslint-plugin-react.</span>deprecatedRules
1.  object <span class="apidocSignatureSpan">eslint-plugin-react.</span>rules



# <a name="apidoc.module.eslint-plugin-react"></a>[module eslint-plugin-react](#apidoc.module.eslint-plugin-react)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
