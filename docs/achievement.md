<h1>Achievement Documentation</h1>
This part of the documentation will cover steamworks.js achievement option in the client function.
<h2>How to make a achievement activate</h2>
To make your achievement activate you must go to your dashboard for your game and go to steam admin then achievement. If you already have an achivement copy the API name, if you don't make and achivement give it a name and the required field's. Remeber to publish your new change's so it can work properly. Here is an example of a achievement being granted.

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

<h2>Checking if a user already has an achivement</h2>
This is similiar to granting a user an achivement but with a couple of change's let's get into it.


```js
// Import's init from steamworks.js to initalize your appid
const { init } = require('steamworks.js')

// Required to initilize your game and access achievement etc
const client = init(480)

// If the achievement "clicking" exist's the achivement will be granted to the user.
if client.achievement.isActivated('ACHIEVEMENT')) {
// You can add other code like console.log() and more
} ```
