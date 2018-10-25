Trip Service Kata
=================

Kata for legacy code hands-on session. The objective is to test and refactor the legacy TripService class.

The end result should be well-crafted code that express the domain.

You can watch the video with my solution. Although quite long, I explain my whole thought process while writting tests, how I break dependencies, the reasons for refactoring and re-desining the code (tests and production code), and why certain steps are important. I also cover how often I commit and why I do it. 

The video is full of tips and tricks that can be used in any language.

https://www.youtube.com/watch?v=_NnElPO5BU0


# PHP

In order to perform the kata, first of all you will need to install all of the dependencies. This can be done using
composer (standing from the *"php"* directory")

```shell
wget http://getcomposer.org/composer.phar
php composer.phar install
```

Next, to execute the unit tests you need run this from the *php* directory

    php bin/phpunit

## Coverage

When running the tests a coverage report should be generated automatically in simple text format and html report.

If you want to visualize it from the browser you can open

    open coverage/report/index.html

in a browser after running the tests.

Enjoy

