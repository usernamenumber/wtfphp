# WTeffingF, PHP?
## Instructions
1. Install `php-cli`, if needed.
1. `cat runme.php`  "*Ok, this includes `foo/main.php`*"
1. `cat foo/main.php` "*Well this just includes a file called `required.php`*"
1. `find .`  "*Oh hey, there are two files called required.php. Well clearly when foo/main.php requires a relative path, it will be relative to that file. It even includes `./` in the path, so anything else would be silly*"
1. `php ./runme.php`
1. Put head through monitor

Brought to you by one of my Moodle modules suddenly crashing on every load because an update to Moodle introduced a file that happened to have the same name as one used in the module. 

Fortunately, this behavior is well-documented... in [a user-contributed comment](http://php.net/manual/en/function.include.php#107685).
