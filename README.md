# ScreenShottr Web 2.0

[ScreenShottr](https://screenshottr.us)

**Note:** Master branch will always contain the latest stable release. All development work to be committed to the "dev" branch.

ScreenShottr Web 2.0 is a fully re-written from the ground up version of the ScreenShottr Web service. Using nodeJS, mongoDB & express as a backend, ScreenShottr Web 2.0 comes with a refreshed look and feel.

  - Anonymously upload files, all encrypted and stored so not even we can see them!
  - No logging, all file uploads are anonymous
  - Let us handling the shortening of URLs, all you have to do is paste! We'll copy the link for you!

ScreenShottr Web 2.0 is an open-source application! Feel free to contribute. See the development section below for more details

### Development

For any developer working on the ScreenShottr Web 2.0 project you must follow the below outlined coding standards. These outline the methods in which we enforce when developing and maintaining the software. Only code following the practices highlighted will be accepted as a valid pull request, regardless of priority.

All our standards follow the [Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html) with a few exceptions.

##### Formatting
___
**Braces** - Are required for all control structures even if the body only contains a single statement.

Allowed:
```javascript
if (someMethod()) {
    runThisMethod();
} 
```
Not Allowed:

```javascript
if (someMethod())
    runThisMethod();
```

Exception - A simple conditional that can fit on one line with NO wrapping and does not contain an else:
*Note*: Ternary operators are allowed.

```javascript
if (miniCondition()) return true;
```

All Braces follow the [K&R](https://google.github.io/styleguide/jsguide.html#formatting-nonempty-blocks) Style as outlined here in the [Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html).




### License


GNU General Public License V3




