# google-libphonenumber
Google phone validation library compiled to vanilla JS

This library exposes a `i18n` object with all the functions provided by the [google libphonenumber library](https://github.com/googlei18n/libphonenumber)

This means that if you plan to use it with angular you should include a binder like this one:
```
// Angular binding for google libphonenumber library
angular.module('i18n', [])
.factory('i18n', function() {
  return i18n; // assumes google libphonenumber has already been loaded on the page
});
```

## How to compile
To compile Google libphonenumber follow these steps: http://stackoverflow.com/a/35401754/1116959
