<h1>Stats Doccumentation</h1>
This part of the Doccumentation will be covering how to access stats and edit stats.

<h2>Getting the value</h2>
Before starting you should check if you already have a stats copy it's API name and follow the example changing it along the way. If you don't have a stat already made you have to make one before starting, to do this go to your app dashboard -> app admin -> Stats & Achievements -> Stats. From there you click on "New Stat" and fill out the information then you copy the API name as we will need that later.

<h2>The code</h2>
This is the code you should use to access your stat's and set the value of the stat's.

```js
// We need to require steamworks.js and initilize the game with our statment's below.
const { init } = require('steamworks.js')

const client = init(480)

// Access the stat you made replace "MoneyStat" with your API name.
if (client.stats.getInt('MoneyStat')) {
    // Add extra code here example console.log()
    client.stats.store(1)
}
```
**To get the int/integer**
```js
// We need to require steamworks.js and initilize the game with our statment's below.
const { init } = require('steamworks.js')

const client = init(480)
// Remeber to replace MoneyStat with your API name.
const getint = client.stats.getInt('MoneyStat') 

// You don't have to use this example you can modify this to your liking also.
console.log(getint)
```
**Note: This isn't the best method to get your int/integer this is just an example, you can change this to make it better.**
