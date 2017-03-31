# PhpStorm Laravel Code Style

This is a code style based on PSR-2, as per Laravel's [Contribution Guide](http://laravel.com/docs/5.4/contributions#coding-style)

To use this coding style, drop the `Laravel.xml` file in the `/config/codestyles/` subfolder within your [configuration directory](https://www.jetbrains.com/phpstorm/help/project-and-ide-settings.html).

This code style has been updated in line with Laravel 5.4, and matches Laravel's code styles as best as possible with PhpStorm's available configuration.

Be mindful of the PHPDoc layout, which dictates `@param` is followed by *two* spaces, the argument type, *two more* spaces, and finally the variable name, which I've not been able to replicate in PhpStorm.
