JQuery File Upload Widget
=========================
Renders a BlueImp jQuery File Upload plugin. That plugin integrates multiple file selection, drag&drop support, progress bars, validation and preview of images.

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist barilee/yii2-jquery-file-upload "*"
```

or add

```
"barilee/yii2-jquery-file-upload": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \barilee\jqueryFileUpload\AutoloadExample::widget(); ?>```