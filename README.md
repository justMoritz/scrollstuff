# scrollstuff
Simple jQuery _“stuff is scrolled into view so let's add a class”_ plugin

## Usage:
### Basic
scrollstuff Extends the jQuery Object with a new method, so the easiest usage is like this:

    $('your-selector-here')..scrollstuff({});

### Advanced
You van also run scrollstuff with arguments

    $('your-selector-here')..scrollstuff({
      classname: 'custom-class-name',
      delay: 700,
      repeat: true
    });

  The scrollstuff object current accepts the following arguments in object notation:
  * classname _(string)_ — name of the class to attach to object. `'this--nowinview'` by default.
  * delay _int_ — delay until class is added, in milliseconds
  * repeat _boolean_ whether or not the animation repeats when it's out and in of view again

#### That's it! Have fun and enjoy the ride and all that good stuff!