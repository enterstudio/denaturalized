# denaturalized

[![CircleCI](https://circleci.com/gh/jebeck/denaturalized.svg?style=svg)](https://circleci.com/gh/jebeck/denaturalized)

JSON datasets of denaturalized (former) citizens by country, starting with the United States.

## data sources

- for the United States, Wikipedia's [list of denaturalized former citizens of the United States](https://en.wikipedia.org/wiki/List_of_denaturalized_former_citizens_of_the_United_States 'Wikipedia: List of denaturalized former citizens of the United States').

Wikipedia has made the text of the data distributed here in JSON format available under a [Creative Commons Attribution-ShareAlike License, 3rd version](https://creativecommons.org/licenses/by-sa/3.0/legalcode 'Creative Commons CC-BY-SA 3.0').

## how to use

If you'd like to use this data in a JavaScript project, simply install it as a dependency via [npm](https://www.npmjs.com/ 'npm'):

```bash
$ npm install --save denaturalized
```

To access the data as an array of JavaScript objects, simply require the package as you would any other dependency installed via npm:

```JavaScript
var data = require('denaturalized');
```

For use outside of JavaScript projects, you can [download the package from GitHub](https://github.com/jebeck/denaturalized/releases/latest).
