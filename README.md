#isEmoji
### ndoe module to check if a string is an emoji

```js
var isEmoji = require('isemoji');

isEmoji('')
// false

isEmoji('some string')
// false

isEmoji('✈️')
// true
```