You should `init` the SDK in the `deviceReady` function, to make sure the native integrations runs. For more details about Cordova [click here]({%- link _documentation/platforms/javascript/cordova.md -%})  

```javascript
onDeviceReady: function() {
  var Sentry = cordova.require("sentry-cordova.Sentry");
  Sentry.init({ dsn: '___PUBLIC_DSN___' });
}
```
