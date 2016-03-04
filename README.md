# poly-filter

[![Build Status](https://travis-ci.org/vguillou/poly-filter.svg?branch=master)](https://travis-ci.org/vguillou/poly-filter)
[![GitHub version](https://badge.fury.io/gh/vguillou%2Fpoly-filter.svg)](https://badge.fury.io/gh/vguillou%2Fpoly-filter)

_A fast and customizable solution for client side filtering of large arrays, built for and with Polymer._

Main features:
- Token based and case-insensitive filtering
- Configurable matching method (`contains`, `startsWith` or `equals`)
- Support for large arrays without browser freeze
- Fully declarative usage with bindable filter query, source array and result array
- Configurable item properties and subproperties to asses
- Support for the 'Google-like' quote (") operator
- Custimozable logical 'OR' operator
- Stop-words support to ignore configured tokens
- Diacritics (accents and other character modifiers) support


## Use it in your project :

Element dependencies are managed via [Bower](http://bower.io/). To install this element,
use this command

    bower install --save poly-filter


## Documentation and demo

Please refer to the <a href="https://vguillou.github.io/webcomponents/poly-filter">component page</a> for more informations.

Here are the direct links to the <a href="https://vguillou.github.io/webcomponents/poly-filter/demo">feature demo</a> and the <a href="https://vguillou.github.io/webcomponents/poly-filter/demo/perf-demo.html">performance demo</a>.


## License

[MIT License](http://opensource.org/licenses/MIT)
