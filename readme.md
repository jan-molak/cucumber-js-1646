# Cucumber.js issue 1646

See cucumber/cucumber-js#1646

## Usage

```
npm install
npm start
```

See:

```
> cucumber-js-1646@1.0.0 start /path/to/jan-molak/cucumber-js-1646
> node index.js

internal/modules/cjs/loader.js:438
      throw e;
      ^

Error [ERR_PACKAGE_PATH_NOT_EXPORTED]: Package subpath './lib/models/test_case_hook_definition' is not defined by "exports" in /path/to/jan-molak/cucumber-js-1646/node_modules/@cucumber/cucumber/package.json
    at throwExportsNotFound (internal/modules/esm/resolve.js:290:9)
    at packageExportsResolve (internal/modules/esm/resolve.js:513:3)
    at resolveExports (internal/modules/cjs/loader.js:432:36)
    at Function.Module._findPath (internal/modules/cjs/loader.js:472:31)
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:867:27)
    at Function.Module._load (internal/modules/cjs/loader.js:725:27)
    at Module.require (internal/modules/cjs/loader.js:952:19)
    at require (internal/modules/cjs/helpers.js:88:18)
    at Object.<anonymous> (/path/to/jan-molak/cucumber-js-1646/index.js:1:32)
```