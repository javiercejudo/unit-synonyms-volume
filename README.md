# unit-synonyms-volume

[![Build Status](https://travis-ci.org/javiercejudo/unit-synonyms-volume.svg)](https://travis-ci.org/javiercejudo/unit-synonyms-volume)
[![Coverage Status](https://coveralls.io/repos/javiercejudo/unit-synonyms-volume/badge.svg?branch=master)](https://coveralls.io/r/javiercejudo/unit-synonyms-volume?branch=master)
[![Code Climate](https://codeclimate.com/github/javiercejudo/unit-synonyms-volume/badges/gpa.svg)](https://codeclimate.com/github/javiercejudo/unit-synonyms-volume)

Volume units synonyms

## Install

    npm i unit-synonyms-volume

## Units

- [Cubic metre](https://en.wikipedia.org/wiki/Cubic_metre)
- [Millilitre](https://en.wikipedia.org/wiki/Millilitre)
- [Litre](https://en.wikipedia.org/wiki/Litre)
- [Cubic inch](https://en.wikipedia.org/wiki/Cubic_inch)
- [Cubic foot](https://en.wikipedia.org/wiki/Cubic_foot)
- [Fluid ounce (imperial and US)](https://en.wikipedia.org/wiki/Fluid_ounce)
- [Gill (imperial and US)](https://en.wikipedia.org/wiki/Gill_(unit))
- [Pint (imperial and US liquid)](https://en.wikipedia.org/wiki/Pint)
- [Gallon (imperial and US liquid)](https://en.wikipedia.org/wiki/Gallon)
- [Dram](https://en.wikipedia.org/wiki/Dram_(unit)#Unit_of_volume)
- [Cup](https://en.wikipedia.org/wiki/Cup_(unit))

## Usage

```js
var synonyms = require('unit-synonyms-volume').synonyms;

synonyms['L']; // => litre
synonyms['cubic meters']; // => cubicMetre
```

## Related projects

- [linear-presets](https://github.com/javiercejudo/linear-presets): linear presets for common units.
- [linear-converter](https://github.com/javiercejudo/linear-converter): flexible linear converter.
