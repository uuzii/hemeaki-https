# \<firebase-image-upload\>

upload images to firebase storage: this is a stripped down image uploader similar to the one in [The Firecast Tutorial: Getting Started with Storage on the Web](https://youtu.be/SpxHVrpfGgU?list=PLl-K7zZEsYLnJVX_0zbKytptZGugPIbJR). The only major difference is it was created as a Polymer element.

This could easily be forked into something more useful and validatey.

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
