# karma-opera-launcher

> Launcher for Opera.

## Installation

The easiest way is to keep `karma-opera-launcher` as a devDependency in your `package.json`.
```json
{
  "devDependencies": {
    "karma": "~0.10",
    "karma-opera-launcher": "~0.1"
  }
}
```

You can simple do it by:
```bash
npm install karma-opera-launcher --save-dev
```

## Configuration
```js
// karma.conf.js
module.exports = function(config) {
  config.set({
    browsers: ['Opera']
  });
};
```

You can pass list of browsers as a CLI argument too:
```bash
karma start --browsers Opera
```

----

For more information on Karma see the [homepage].


[homepage]: http://karma-runner.github.com
