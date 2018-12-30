### Detect browsers installed on a machine

```javascript
//import
import browsers from 'detect-browsers';

//Get installed browsers
browsers.getInstalledBrowsers()
  .then( list=> console.log(list))
  .catch( error => console.error(error));

//Open browser
browsers.openBrowser('Google Chrome');
```

License -> MIT