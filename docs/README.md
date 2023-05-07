# Steamworks.js Doccumentation
Welcome to the steamworks.js doccumentation here's a quick FAQ before you ready the docs.
## FAQ
Here we will quickly go over how to create a achievement 

```js 
// Import's init from steamworks.js to initalize your appid
const { init } = require('steamworks.js')

// Required to initilize your game and access achievement etc
const client = init(480)

// If the achievement "clicking" exist's the achivement will be granted to the user.
if (client.achievement.activate('ACHIEVEMENT')) {
// You can add other code like console.log() and more
}
```
## Pages

* (231)[www.google.com]
