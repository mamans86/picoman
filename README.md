# Picoman Theme for TCExam #
Mobile First Design TCExam Theme built on top Pico.css (https://picocss.com)
This theme only make changes view on Public area. For a while the Admin theme use the default theme of TCExam. Maybe if any spare time available i will create the admin theme too.
## Features ##
1. Mobile First Design, Responsive, make TCExam more user friendly on small Device
2. Bootstrap like user interface
3. Password Field Toggler
4. Font Resizer Utility on Public Test Taker
5. Unsure Button to mark unsure question (using HTML5 LocalStorage to store unsure question index)
6. Maybe, it Work on any modern browser today :)

## Usage ##
1. Go to /public/config/ of your TCExam installation. Make sure you are using TCExam version 14.4.0 or higher.
2. Edit the file tce_config.php with Text Editor
3. In K_PUBLIC_THEME change `default` to `picoman` just like this example
```php
/**
 * Theme for the public area
 */
define('K_PUBLIC_THEME', 'picoman');
```
4. Download 3 files are provided here: `picoman.css`, `picoman_rtl.css` and `picoman.php`
5. Place `picoman.css` and `picoman_rtl.css` to `/public/styles/` directory
6. Place `picoman.php` to `/public/config/theme/` directory
7. Done

## Additional License ##
Please keep my credit and link visible and reachable. thanks :) 
