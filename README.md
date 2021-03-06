# Vue.js component to render a modal window

[![Latest Version on NPM](https://img.shields.io/npm/v/vue-modal.svg?style=flat-square)](https://npmjs.com/package/vue-modal)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![Build Status](https://img.shields.io/travis/stuartmccord/vue-modal/master.svg?style=flat-square)](https://travis-ci.org/stuartmccord/vue-modal)

An easy to use, customizable Vue.js modal component.

## Installation

You can install the package via yarn:

```bash
yarn add vue-modal
```

or npm:

```bash
npm install vue-modal --save
```

Register the component within your application ```Vue.component('modal', require('vue-modal'));```


## Usage

The HTML contents of the modal go between the ```<modal>``` tags:

```html
    <div id="app">
        <modal :show="false">
            Modal content
        </modal>
    </div>
```

Set the ```show``` attribute's value to ```true``` to display the modal, this can be done via and expression/variable that evaluates to true.

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Testing

```bash
yarn test
```

## Security

If you discover any security related issues, please contact stuart.mccord@gmail.com instead of using the issue tracker.

## Credits

- [Stuart McCord](https://github.com/stuartmccord)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
