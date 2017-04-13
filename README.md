# `alexa-skill-demo`

`alexa-skill-demo` shows how to get started with a basic Alexa skill.

## Sample Intent: HelloWorld

Refer to the [Alexa Skills doc](https://developer.amazon.com/) for more details

```javascript
const lib = require('lib');

module.exports = function (slots, callback) {

  return callback(null, `Hello World`);

};
```

This intent will cause Alexa to respond with "Hello World." You can see that
intents defined in this way receive `slots` automatically, and are executed
with a `callback` - the first parameter is an `Error` parameter, and if provided,
Alexa will respond with an error. Otherwise Alexa will respond with the string
provided by the second parameter.

## Contributors

* Steven Spann <sspann21@gmail.com> - Software Developer
