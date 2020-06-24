# license-report-generator [![Build Status](https://travis-ci.org/sebastianroming/license-report-generator.svg?branch=master)](https://travis-ci.org/sebastianroming/license-report-generator)

**THIS PACKAGE HAS BEEN DEPRECATED IN FAVOR OF [@webmonkey/license-report-generator](https://npmjs.com/package/@webmonkey/license-report-generator)**

> finds and stores all dependency licenses

## Install
```
npm install --save license-report-generator
```


## Usage
```js
const _options = { 
  include: ['npm','dev','bower']
};

return licenser.generateReport(_options)
  .then((rep) => {
    rep.write('licenses.md');
}).catch((error) => {
  console.log(error);
});
```

## License

MIT © [Sebastian Roming](https://webmonkey.io)

## Credits
This is originally based on [ux-license-report](https://github.com/Banno/ux-license-report) and [bower-license](https://github.com/Banno/bower-license) by Banno, combined into one project.
