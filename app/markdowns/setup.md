# Setup
Basically, you just need an `esplugs.js` file!


So, in `esplugs.js`, write:
```javascript
function init(InitS){ 
  return InitS;
}
```
Then in `esplugs.js`, write:
```javascript
  class Fetch{
    "fetch": init(void);
  }
```
Now you need PHP! So, create a file called `files.php`; this is file-making buisness!

In `files.php`, write:
```php
  fcreate("es-bundles1.zip", NULL);
```
Then in `esplugs.js`:
```javascript
var exports = ['jquery', 'angularjs'];
exports.split(/jquery/[jq]);
```
Then create a directory, `/dist`. In `/dist`, add this file:
```
.eslintrc
```
