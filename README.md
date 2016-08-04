>This repository is part of the [Pelias](http://pelias.io)
>project. Pelias is an open-source, open-data geocoder built by
>[Mapzen](https://www.mapzen.com/) that also powers [Mapzen Search](https://mapzen.com/projects/search). Our
>official user documentation is [here](https://mapzen.com/documentation/search/).

# `pelias-categories`

This module is intended to represent the Pelias category taxonomy. It is the place to ask what categories exist, as well as what tags they correspond to in various data sets.

## Installation

```
npm install pelias-categories
```

## Usage

```javascript
var categories = require('pelias-categories');

if (categories.isValidCategory('food')) {
  console.log('food is a valid category');
}
```

## Contributing

Please fork and pull request against upstream master on a feature branch. Pretty please; provide unit tests. :tada:

## Unit tests

You can run the unit test suite using the command:

```bash
$ npm test
```
