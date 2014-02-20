*This repository is a mirror of the [component](http://component.io) module [manuelstofer/backbone-pflock](http://github.com/manuelstofer/backbone-pflock). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/manuelstofer-backbone-pflock`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# Backbone-Pflock

![Build status](https://api.travis-ci.org/manuelstofer/backbone-pflock.png)

Two way data bindings for [Backbone](http://backbonejs.org) models using [Pflock](https://github.com/manuelstofer/pflock).


### Usage

Backbone-Pflock provides an adapter to use Backbone models with Pflock.

```Javascript
var adapter = require('backbone-pflock');
var model = new Backbone.Model({
    name: 'bla',
    description: 'anything'
});

var el = document.getElementById('model-root-node');

bind(el, model);
```

