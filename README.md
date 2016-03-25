# use-child-theme.php
This PHP class automatically creates a child theme if needed.

<img src="http://i.imgur.com/dvLchUj.png" width="508" height="167" />

### How it works

_If a child theme isn't active..._
* A child theme is created (if needed)
* A WP notice allows for 1-click child theme activation
* The parent theme's settings are copied to the child theme

### How to use it

If you're a theme developer, include `use-child-theme.php` in your theme, then add this code into functions.php:

```php
include( 'use-child-theme.php' );
```
### Changelog

**0.3**
* Code cleanup

**0.2**
* Create a child theme (if needed) only when user clicks "Activate"
* Hide notice for 24 hours when dismissed
* Support .gif and .jpeg screenshots

**0.1**
* Initial release
