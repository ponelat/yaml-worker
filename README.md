# YAML Worker

> JS-YAML and YAML-JS wrapper with Worker API

#### Installation

Install using Bower or npm

```
npm install --save yaml-worker
```

```
bower install --save yaml-worker
```

#### Usage

Use `YAMLWorker`:

```js
var worker = new YAMLWorker();

worker.load('yaml: true', function(error, result) {
  console.log(result); // {"yaml": true}
});
```

### License
MIT
