My Extension
============
Demo

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist tas/yii2-myext "*"
```

or add

```
"tas/yii2-myext": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \tas\myext\AutoloadExample::widget(); ?>```