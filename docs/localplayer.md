<h1>Localplayer Doccumentation</h1>
This part of the documentation will cover steamworks.js localplayer option in the client function.
<h2>How to get a local players username</h2>
To get a local players username is really simple to do take a look at the code and it will explain how to access a local player's username.

```javascript
// Import's init from steamworks.js to initalize your appid
const { init } = require('steamworks.js')

// Required to initilize your game and access achievement etc
const client = init(480)

// This will access the localplayer's name this can also be contained in a if statment.
client.localplayer.getName 
// You can add other code here like a console.log
```

<h2>How to get a local players username</h2>
