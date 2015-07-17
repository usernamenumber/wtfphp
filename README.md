# WTeffingF, PHP?
## Instructions
1. Install `php-cli`, if needed.
1. `cat runme.php`  "Ok, this includes foo/main.php"
1. `cat foo/main.php` "Well this just includes a file called required.php"
1. `find .`  "Oh hey, there are two files called required.php. Well clearly when foo/main.php requires a relative path, it will be relative to that file. Anything else would be silly"
1. `php ./runme.php`
1. Put head through monitor

