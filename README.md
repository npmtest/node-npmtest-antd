# npmtest-antd

#### basic test coverage for  [antd (v2.9.3)](http://ant.design/)  [![npm package](https://img.shields.io/npm/v/npmtest-antd.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-antd) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-antd.svg)](https://travis-ci.org/npmtest/node-npmtest-antd)

#### An enterprise-class UI design language and React-based implementation

[![NPM](https://nodei.co/npm/antd.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/antd)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-antd/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-antd/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-antd/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-antd/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-antd/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-antd/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-antd/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-antd/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-antd/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-antd/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-antd/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-antd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-antd/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-antd/build/test-report.html](https://npmtest.github.io/node-npmtest-antd/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-antd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-antd/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-antd/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-antd/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-antd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-antd/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-antd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-antd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/ant-design/ant-design/issues"
    },
    "contributors": [
        {
            "name": "ant"
        }
    ],
    "dependencies": {
        "array-tree-filter": "~1.0.0",
        "babel-runtime": "6.x",
        "classnames": "~2.2.0",
        "css-animation": "^1.2.5",
        "dom-closest": "^0.2.0",
        "lodash.debounce": "^4.0.8",
        "moment": "^2.18.1",
        "object-assign": "~4.1.0",
        "omit.js": "^0.1.0",
        "prop-types": "^15.5.7",
        "rc-animate": "~2.3.0",
        "rc-calendar": "~8.0.0",
        "rc-cascader": "~0.11.0",
        "rc-checkbox": "~1.5.0",
        "rc-collapse": "~1.7.0",
        "rc-dialog": "~6.5.0",
        "rc-dropdown": "~1.4.8",
        "rc-editor-mention": "~0.5.2",
        "rc-form": "~1.3.0",
        "rc-input-number": "~3.4.4",
        "rc-menu": "~5.0.9",
        "rc-notification": "~1.4.0",
        "rc-pagination": "~1.8.0",
        "rc-progress": "~2.1.0",
        "rc-radio": "~2.0.0",
        "rc-rate": "~2.1.0",
        "rc-select": "~6.8.0",
        "rc-slider": "~7.0.0",
        "rc-steps": "~2.5.0",
        "rc-switch": "~1.4.2",
        "rc-table": "~5.2.13",
        "rc-tabs": "~7.3.0",
        "rc-time-picker": "~2.3.3",
        "rc-tooltip": "~3.4.2",
        "rc-tree": "~1.4.0",
        "rc-tree-select": "~1.9.0",
        "rc-upload": "~2.3.0",
        "rc-util": "^4.0.1",
        "react-lazy-load": "^3.0.10",
        "react-slick": "~0.14.2",
        "shallowequal": "^0.2.2",
        "warning": "~3.0.0"
    },
    "description": "An enterprise-class UI design language and React-based implementation",
    "devDependencies": {
        "@types/react": "^15.0.8",
        "@types/react-dom": "~0.14.18",
        "antd-demo-jest": "^1.0.5",
        "antd-tools": "~0.19.1",
        "babel-cli": "^6.18.0",
        "babel-eslint": "^7.1.0",
        "babel-jest": "^19.0.0",
        "babel-plugin-import": "^1.0.0",
        "babel-plugin-transform-runtime": "^6.23.0",
        "babel-preset-es2015": "^6.18.0",
        "babel-preset-react": "^6.16.0",
        "babel-preset-stage-0": "^6.16.0",
        "bezier-easing": "^2.0.3",
        "bisheng": "^0.23.0",
        "bisheng-plugin-antd": "^0.13.2",
        "bisheng-plugin-description": "^0.1.1",
        "bisheng-plugin-react": "^0.5.0",
        "bisheng-plugin-toc": "^0.4.0",
        "color-standalone": "^0.11.6",
        "cross-env": "^4.0.0",
        "css-split-webpack-plugin": "^0.2.3",
        "dekko": "^0.2.0",
        "delegate": "^3.1.2",
        "dora-plugin-upload": "^0.3.1",
        "enquire.js": "^2.1.1",
        "enzyme": "^2.6.0",
        "enzyme-to-json": "^1.3.0",
        "eslint": "^3.0.1",
        "eslint-config-airbnb": "latest",
        "eslint-plugin-babel": "^4.0.0",
        "eslint-plugin-import": "^2.1.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "eslint-plugin-markdown": "1.0.0-beta.4",
        "eslint-plugin-react": "^6.10.3",
        "eslint-tinker": "^0.4.0",
        "fetch-jsonp": "^1.0.3",
        "glob": "^7.1.1",
        "jest": "^19.0.2",
        "jsonml.js": "^0.1.0",
        "lint-staged": "^3.3.1",
        "mockdate": "^2.0.1",
        "moment-timezone": "^0.5.5",
        "pre-commit": "^1.2.2",
        "querystring": "^0.2.0",
        "rc-queue-anim": "^0.13.2",
        "rc-scroll-anim": "^1.0.3",
        "rc-tween-one": "^1.1.2",
        "react": "^15.0.0",
        "react-addons-test-utils": "^15.5.1",
        "react-color-standalone": "^2.4.2-1",
        "react-copy-to-clipboard": "^4.0.1",
        "react-document-title": "^2.0.1",
        "react-dom": "^15.0.0",
        "react-github-button": "^0.1.1",
        "react-intl": "^2.0.1",
        "react-stateless-wrapper": "^1.0.2",
        "react-sublime-video": "^0.2.0",
        "react-test-renderer": "^15.5.4",
        "reqwest": "^2.0.5",
        "rimraf": "^2.5.4",
        "stylelint": "^7.8.0",
        "stylelint-config-standard": "^16.0.0",
        "typescript": "~2.2.1",
        "typescript-babel-jest": "^1.0.2",
        "values.js": "^1.0.3",
        "xhr2": "^0.1.3"
    },
    "directories": {},
    "dist": {
        "shasum": "5b40349827fab882d73bd97707d614709a620863",
        "tarball": "https://registry.npmjs.org/antd/-/antd-2.9.3.tgz"
    },
    "files": [
        "dist",
        "lib"
    ],
    "gitHead": "2325da5c3e18faf5dee8477312b66a5ff0d6fb60",
    "homepage": "http://ant.design/",
    "jest": {
        "setupFiles": [
            "./tests/setup.js"
        ],
        "moduleFileExtensions": [
            "ts",
            "tsx",
            "js",
            "jsx",
            "json",
            "md"
        ],
        "modulePathIgnorePatterns": [
            "/_site/"
        ],
        "testPathIgnorePatterns": [
            "dekko",
            "/node_modules/",
            "node"
        ],
        "transform": {
            "\\.tsx?$": "./node_modules/typescript-babel-jest",
            "\\.js$": "./node_modules/babel-jest",
            "\\.md$": "./node_modules/antd-demo-jest"
        },
        "testRegex": ".*\\.test\\.js$",
        "collectCoverageFrom": [
            "components/**/*.{ts,tsx}",
            "!components/*/style/index.tsx"
        ],
        "transformIgnorePatterns": [
            "/node_modules/",
            "/dist/antd.js"
        ],
        "snapshotSerializers": [
            "enzyme-to-json/serializer"
        ]
    },
    "keywords": [
        "ant",
        "design",
        "react",
        "react-component",
        "component",
        "components",
        "ui",
        "framework",
        "frontend"
    ],
    "license": "MIT",
    "lint-staged": {
        "components/**/*.tsx": [
            "lint-staged:ts"
        ],
        "{tests,site,scripts,components}/**/*.{js,jsx}": [
            "lint-staged:es"
        ],
        "{site,components}/**/*.less": "stylelint --syntax less",
        "components/*/demo/*.md": [
            "lint-staged:demo"
        ]
    },
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "benjycui"
        }
    ],
    "name": "antd",
    "optionalDependencies": {},
    "pre-commit": [
        "lint-staged"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ant-design/ant-design.git"
    },
    "scripts": {
        "authors": "git log --format='%aN <%aE>' | sort -u | grep -v 'users.noreply.github.com' | grep -v 'gitter.im' | grep -v '.local>' | grep -v 'alibaba-inc.com' | grep -v 'alipay.com' | grep -v 'taobao.com' > AUTHORS.txt",
        "compile": "antd-tools run compile",
        "deploy": "antd-tools run clean && npm run site && bisheng gh-pages --push-only",
        "dist": "antd-tools run dist",
        "lint": "npm run lint:ts && npm run lint:es && npm run lint:demo && npm run lint:style",
        "lint-fix": "npm run lint-fix:code && npm run lint-fix:demo",
        "lint-fix:code": "eslint --fix tests site scripts components ./.eslintrc.js ./webpack.config.js --ext '.js,.jsx'",
        "lint-fix:demo": "eslint-tinker ./components/*/demo/*.md",
        "lint-fix:ts": "npm run tsc && antd-tools run ts-lint-fix",
        "lint-staged": "lint-staged",
        "lint-staged:demo": "cross-env RUN_ENV=DEMO eslint --ext '.md'",
        "lint-staged:es": "eslint ./.eslintrc.js ./webpack.config.js",
        "lint-staged:ts": "tsc && node node_modules/tslint/bin/tslint -c node_modules/antd-tools/lib/tslint.json",
        "lint:demo": "cross-env RUN_ENV=DEMO eslint components/*/demo/*.md --ext '.md'",
        "lint:es": "eslint tests site scripts components ./.eslintrc.js ./webpack.config.js --ext '.js,.jsx'",
        "lint:style": "stylelint \"{site,components}/**/*.less\" --syntax less",
        "lint:ts": "npm run tsc && antd-tools run ts-lint",
        "pre-publish": "npm run test-all && node ./scripts/prepub",
        "prepublish": "antd-tools run guard",
        "pub": "antd-tools run pub",
        "site": "bisheng build --ssr -c ./site/bisheng.config.js",
        "start": "bisheng start -c ./site/bisheng.config.js --no-livereload",
        "test": "jest",
        "test-all": "./scripts/test-all.sh",
        "tsc": "tsc"
    },
    "title": "Ant Design",
    "typings": "lib/index.d.ts",
    "version": "2.9.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
