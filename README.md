# nepali-names [![Build Status](https://travis-ci.org/bravegurkha/nepali-names.svg?branch=master)](https://travis-ci.org/bravegurkha/nepali-names)

![](kali.jpg)

Get popular nepali names.

# How To Install

```sh

  $ npm install -g nepai-names

```

#How to use

To get random male and female names. Following function can be used.

```js

  let randNames = require('nepali-names');

  randNames.all // To get all the nepali names.
  randNames.randomFemale() // To get random nepali female names.
  randNames.randomMale() // To get random nepali male names.
  randNames.allFemale // To get all the nepali female names.
  randNames.allMale // To get all the nepali male names.
```

# Data Source

  The data was taken from :
  **[studenton/gender-data](https://github.com/studenton/gender-data)**

# LICENSE

This is under [MIT](https://opensource.org/licenses/mit-license.php) Licesnse.
