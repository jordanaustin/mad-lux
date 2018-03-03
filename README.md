# \<mad-lux\>

Ambient Light Sensor Polymer element.

⚠️ NOTE: This uses the generic sensor API which isn't availabile in every browser yet. Try FireFox, this seems to be well supported right now.

## Using the <mad-lux> element

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="mad-lux.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<h1>Illuminance: [[illuminance]]lux</h1>
<p>👋 wave your hand across your light sensor</p>

<mad-lux></mad-lux>
```


## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
