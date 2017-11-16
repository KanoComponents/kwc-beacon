# \<kwc-beacon\>

A call-to-action beacon that will position itself to highlight a target element.

 - What is it called?
     - kwc-beacon
 - What is it made out of?
     - A beacon, a ring and a ripple, with infinite animation. There is also a sound effect for the first five iterations of the animation cycle.
 - What variants are needed?
     - target: Either an HTML element or a DOMRect object. There is an advantage of passing an HTML element to the beacon, as it will automatically update its position on window resize
     - angle: The beacon can be positioned around its target element with a range of 0 - 360 degree
     - offset: The beacon will sit on the edge of its target with an offset that is configurable
     - audioPath: To overwrite the default sound effect.
     - halt: To hide the beacon.

## Installation
Clone this repository.
Run `bower i`

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
