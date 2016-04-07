## Select

[![GitHub version](https://badge.fury.io/gh/HubSpot%2Fselect.svg)](http://badge.fury.io/gh/HubSpot%2Fselect)

------

### This is a No-[Tether](https://github.com/HubSpot/tether)-Depend Select.js version which is originally forked from https://github.com/HubSpot/select . All I did is removed [Tether](https://github.com/HubSpot/tether) Dependency.

------

Select.js is a Javascript and CSS library for creating styleable select elements.  It aims to reproduce the behavior of native controls as much as is possible, while allowing for complete styling with CSS.

## Install

__Dependencies__

- ~~__[Tether](https://github.com/HubSpot/tether)__~~ (removed)

Installing via `npm` and `bower` will bring in the above dependencies as well.

__npm__

```sh
$ npm install tether-select
```

__bower__

```sh
$ bower install tether-select
```

## Usage

```javascript
let selectInstance = new Select({
  el: document.querySelector('select.select-target'),
  className: 'select-theme-default'
})
```

[API Documentation](http://github.hubspot.com/select)

[Demo](http://github.hubspot.com/select/docs/welcome)

## Contributing

We encourage contributions of all kinds. If you would like to contribute in some way, please review our [guidelines for contributing](CONTRIBUTING.md).

## License

Copyright © 2015 HubSpot - [MIT License](LICENSE)

