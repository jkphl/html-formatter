# jkphl/html-formatter

[![Build Status][travis-image]][travis-url]  [![Scrutinizer Code Quality][scrutinizer-image]][scrutinizer-url] [![Code Climate][codeclimate-image]][codeclimate-url] [![Documentation Status][readthedocs-image]][readthedocs-url] [![Clear architecture][clear-architecture-image]][clear-architecture-url]

> A simple and opinionated HTML5 source code formatter

## Documentation

Please find the [project documentation](doc/index.md) in the `doc` directory. We recommend [reading it](http://jkphl-html-formatter.readthedocs.io/) via *Read the Docs*.

## Installation

This library requires PHP >=5.6 or later. I recommend using the latest available version of PHP as a matter of principle. It has no userland dependencies.

## Dependencies

![Composer dependency graph](https://rawgit.com/jkphl/html-formatter/master/doc/dependencies.svg)

## Quality

To run the unit tests at the command line, issue `composer install` and then `phpunit` at the package root. This requires [Composer](http://getcomposer.org/) to be available as `composer`, and [PHPUnit](http://phpunit.de/manual/) to be available as `phpunit`.

This library attempts to comply with [PSR-1][], [PSR-2][], and [PSR-4][]. If you notice compliance oversights, please send a patch via pull request.

## Contributing

Found a bug or have a feature request? [Please have a look at the known issues](https://github.com/jkphl/html-formatter/issues) first and open a new issue if necessary. Please see [contributing](CONTRIBUTING.md) and [conduct](CONDUCT.md) for details.

## Security

If you discover any security related issues, please email joschi@tollwerk.de instead of using the issue tracker.

## Credits

- [Joschi Kuphal][author-url]
- [All Contributors](../../contributors)

## License

Copyright © 2018 [Joschi Kuphal][author-url] / joschi@tollwerk.de. Licensed under the terms of the [MIT license](LICENSE).


[travis-image]: https://secure.travis-ci.org/jkphl/html-formatter.svg
[travis-url]: https://travis-ci.org/jkphl/html-formatter
[scrutinizer-image]: https://scrutinizer-ci.com/g/jkphl/html-formatter/badges/quality-score.png?b=master
[scrutinizer-url]: https://scrutinizer-ci.com/g/jkphl/html-formatter/?branch=master
[codeclimate-image]: https://lima.codeclimate.com/github/jkphl/html-formatter/badges/gpa.svg
[codeclimate-url]: https://lima.codeclimate.com/github/jkphl/html-formatter
[readthedocs-image]: https://readthedocs.org/projects/jkphl-html-formatter/badge/?version=latest
[readthedocs-url]: http://jkphl-html-formatter.readthedocs.io/en/latest/?badge=latest
[clear-architecture-image]: https://img.shields.io/badge/Clear%20Architecture-%E2%9C%94-brightgreen.svg
[clear-architecture-url]: https://github.com/jkphl/clear-architecture
[author-url]: https://jkphl.is
[PSR-1]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md
[PSR-2]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md
[PSR-4]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-4-autoloader.md
