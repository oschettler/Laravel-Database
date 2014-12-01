This fork fixes a pagination bug in the original

Laravel Database
================

Laravel Database was created by, and is maintained by [Graham Campbell](https://github.com/GrahamCampbell), and provides some extra database stuff for [Laravel 5](http://laravel.com). Feel free to check out the [change log](CHANGELOG.md), [releases](https://github.com/GrahamCampbell/Laravel-Database/releases), [license](LICENSE.md), [api docs](http://docs.grahamjcampbell.co.uk), and [contribution guidelines](CONTRIBUTING.md).

![Laravel Database](https://cloud.githubusercontent.com/assets/2829600/4432283/a9868ffa-468c-11e4-955e-c46ea13b43a5.PNG)

<p align="center">
<a href="https://travis-ci.org/GrahamCampbell/Laravel-Database"><img src="https://img.shields.io/travis/GrahamCampbell/Laravel-Database/master.svg?style=flat-square" alt="Build Status"></img></a>
<a href="https://scrutinizer-ci.com/g/GrahamCampbell/Laravel-Database/code-structure"><img src="https://img.shields.io/scrutinizer/coverage/g/GrahamCampbell/Laravel-Database.svg?style=flat-square" alt="Coverage Status"></img></a>
<a href="https://scrutinizer-ci.com/g/GrahamCampbell/Laravel-Database"><img src="https://img.shields.io/scrutinizer/g/GrahamCampbell/Laravel-Database.svg?style=flat-square" alt="Quality Score"></img></a>
<a href="LICENSE.md"><img src="https://img.shields.io/badge/license-Apache%202.0-brightgreen.svg?style=flat-square" alt="Software License"></img></a>
<a href="https://github.com/GrahamCampbell/Laravel-Database/releases"><img src="https://img.shields.io/github/release/GrahamCampbell/Laravel-Database.svg?style=flat-square" alt="Latest Version"></img></a>
</p>


## Installation

[PHP](https://php.net) 5.4+ or [HHVM](http://hhvm.com) 3.3+, and [Composer](https://getcomposer.org) are required.

To get the latest version of Laravel Database, simply add the following line to the require block of your `composer.json` file:

```
"graham-campbell/database": "0.2.*"
```

You'll then need to run `composer install` or `composer update` to download it and have the autoloader updated.

You can now utilise the classes in this package to speed up writing Laravel packages further. There are no service providers to register.

#### Looking for a laravel 4 compatable version?

Checkout the [0.1 branch](https://github.com/GrahamCampbell/Laravel-Database/tree/0.1), installable by requiring `"graham-campbell/database": "0.1.*"`.


## Configuration

Laravel Database requires no configuration. Just follow the simple install instructions and go!


## Usage

There is currently no usage documentation besides the [API Documentation](http://docs.grahamjcampbell.co.uk) for Laravel Database.

You may see an example of implementation in [Laravel Credentials](https://github.com/GrahamCampbell/Laravel-Credentials) or [Bootstrap CMS](https://github.com/GrahamCampbell/Bootstrap-CMS).


## License

Apache License

Copyright 2014 Graham Campbell

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

 http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
