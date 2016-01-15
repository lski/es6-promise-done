ES6-Promise-Done
================

This project is designed to add a 'done' method to a global Promise object via NPM or Bower. The spec does not include a done method but it can be quite useful. To read more about Promises I recommend https://www.promisejs.org/.

Installation
------------

You can use either Bower or NPM

```
npm install git:lski/es6-promise-done --save
// or
bower install https://github.com/lski/es6-promise-done.git --save
```

Notes
-----

I must state I did __NOT__ write the code, despite its small size and simple patten, it was written by Forbes Lindesay and supplied by https://www.promisejs.org/. I am simply making it available in a way that can be installed via Bower or NPM to be used either in the browser or global environment where the CommonJS pattern doesnt exist. 

The npm package promises by Forbes Lindesay does include this done extension however the promises implementation available via NPM requires the NPM pattern.

Additionally this can be used with the [es6-promise](https://github.com/jakearchibald/es6-promise) library that shims the Promise/A+ spec available on Bower and NPM but despite the name has no affiliation with it.