# imgapi-ui

This a webfrontend based on the [datasets.at](http://datasets.at) frontend but
I've changed some stuff to support the
[sdc-imgapi](https://github.com/joyent/sdc-imgapi).

## projects used
- [Brunch](http://brunch.io/)
- [AngularJS](http://angularjs.org/)
- [moment.js](http://momentjs.com/)
- [Bootstrap](http://twitter.github.com/bootstrap/)

## development
1. install brunch `npm install -g brunch` (you'll need to have nodejs and npm already installed)
2. install development dependencies with `npm install`
3. build the project with `brunch build`
4. upload everything in `public/` to your destination server

to do quick changes and test locally you can use the included web-server

1. run `brunch watch`
2. run `scripts/web-server.js`
3. open [the development version](http://localhost:8000/_public/index.html) in your browser

a `/datasets` file is already included so that all basic functions should be usable
