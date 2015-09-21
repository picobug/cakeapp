# App Template CakePHP2

App Template skeleton with some custom for use

## Requirements

PHP 5.4 and above.

FriendsOfCake encourages the use of composer and it's best not to mix composer with git submodules for
dependency management. If you need to use submodules you might notice `/vendor` and `/Plugin` folders are
ignored by git. Composer creates those directories when installing vendors and plugins.

There a few ways to solve this:
- edit the `.gitignore` file
- use the `-f` param with `git add Plugin/SomePlugin -f`
- use `app/Plugin` and `app/Vendor` for your submodules.

 [1]: http://book.cakephp.org/2.0/en/installation/url-rewriting.html

## Included packages
The application template comes with some dependencies already included in the composer file. These are designed to help you get up and running quickly.

* [friendsofcake/Crud](https://github.com/friendsofcake/app-template)
* [friendsofcake/Crud](https://github.com/friendsofcake/crud)
* [josegonzalez/dotenv](https://github.com/josegonzalez/php-dotenv)
* [ad7six/dsn](https://github.com/AD7six/php-dsn)

To find out how to make the most of these packages, please read their respective readme files.
