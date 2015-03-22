MongoDb Extension for Yii 2
===========================

This extension provides the [MongoDB](http://www.mongodb.org/) integration for the Yii2 framework.

For license information check the [LICENSE](LICENSE.md)-file.

Installation
------------

This extension requires [MongoDB PHP Extension](http://us1.php.net/manual/en/book.mongo.php) version 1.5.0 or higher.

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist yiisoft/yii2-mongodb
```

or add

```
"yiisoft/yii2-mongodb": "~2.0.0"
```

to the require section of your composer.json.

Configuration
-------------

To use this extension, simply add the following code in your application configuration:

```php
return [
    //....
    'components' => [
        'mongodb' => [
            'class' => '\yii\mongodb\Connection',
            'dsn' => 'mongodb://developer:password@localhost:27017/mydatabase',
        ],
    ],
];
```
