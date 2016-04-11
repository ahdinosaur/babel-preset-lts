# babel-preset-lts

> babel preset to use Node LTS (@4.2+) code in the browser

## install

```sh
$ npm install --save-dev babel-preset-lts
```

## usage

### via `.babelrc` (recommended)

**.babelrc**

```json
{
  "presets": ["lts"]
}
```

### via CLI

```sh
$ babel script.js --presets lts
```

### via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["lts"]
});
```

## license

The Apache License

Copyright &copy; 2016 Michael Williams

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
