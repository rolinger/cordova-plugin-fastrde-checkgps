# phonegap-checkGPS
Plugin to Check if GPS enabled on iOS and Android

## install
```
yourAppDir$ cordova plugin add https://github.com/rolinger/phonegap-checkGPS.git
```

## usage

```javascript
CheckGPS.check(function(){
    //GPS is enabled!

  },
  function(){
    //GPS is disabled!

  });
```
