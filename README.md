Ghosts Users for Wordpress
================

This set of functions allow to create hidden and uneditable users for wordpress.

## Description

You can create how many users (ghosts) that you want with custom details: Username, Role, Password and email.
For this users will be:
 - hidden visibility on the users list in WP backend
 - disabled password reset ability
 - disabled password edit ability
 - automatically recreate all users profiles when deleted

## Usage

Three steps to use it:
 - Put the file in your WP theme folder.
 - Include it in `functions.php` file pasting this command at the end of file:
   ```php
      include_once('ghosts-functions.php');
   ```
 - Populate the Ghosts array in first lines of `ghosts-functions.php`

## Need more tools?
Visit [Wordpress Tools](http://wptools.it).

## Author

made with ❤️ and ☕️ by [weLaika](http://dev.welaika.com)

## License

(The MIT License)

Copyright © 2014-2018 weLaika

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the ‘Software’), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED ‘AS IS’, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

