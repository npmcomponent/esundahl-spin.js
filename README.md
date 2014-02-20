*This repository is a mirror of the [component](http://component.io) module [esundahl/spin.js](http://github.com/esundahl/spin.js). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/esundahl-spin.js`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# spin.js

An animated CSS3 loading spinner with VML fallback for IE.

 * No images, no external CSS
 * No dependencies
 * Highly configurable
 * Resolution independent
 * Uses VML as fallback in old IEs
 * Uses @keyframe animations, falling back to setTimeout()
 * Works in all major browsers, including IE6
 * Small footprint (~1.9K gzipped)
 * MIT License

## Usage

```javascript
var spinner = new Spinner({color:'#fff', lines: 12});
spinner.spin(target);
console.log(spinner.spinning); // true
spinner.stop();
console.log(spinner.spinning); // false
```

For an interactive demo and a list of all supported options please refer to the [project's homepage](http://fgnass.github.com/spin.js).
