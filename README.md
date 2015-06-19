# Subsub.js

Subsub is a module that allows you to subscribe to the same pubnub channel multiple times.

# Usage

```
subsub.subscribe(pubnub, channel, connect, callback);
```

Option | Explanation
-------|-----------
pubnub | Your PubNub javascript object.
channel | The string of the PubNub channel to subscribe to
connect | Optional callback to call when PubNub connects
callback | function to fire when a message is recieved. ```Works same way as pubnub.subscribe```