# &lt;wp-collect-menu&gt;

Polymer 1.2 element element to output json in a 'pretty' way.

Check out the [demo](http://mrpharderwijk.github.io/pretty-json/)

## Setup
Install with bower or [download the zip](https://github.com/mrpharderwijk/pretty-json/archive/v1.0.0.zip)
```bash
bower install --save mrpharderwijk/pretty-json
```
Import it in your code
```html
<!-- for relative paths -->
<link rel="import"href="../bower_components/pretty-json/pretty-json.html">
```

## Usage
To retrieve all pages use the following markup:

```html
  <pretty-json
    input-data="JSON_OBJ"></pretty-json>
```

## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview your element at
`http://localhost:8080/components/pretty-json/`.

## Contribute
Feel free to extend it or propose new functionality
