yii-fontawesome
===============

A fontawesome wrapper for Yii 1.X

Installation
============

Using Composer:

Simply add a dependency on "pelmennoteam/yii-fontawesome" to your project's composer.json file if you use Composer to manage the dependencies of your project. Here is a minimal example of a composer.json

```
{
    "require": {
        "pelmennoteam/yii-fontawesome": "dev-master"
    }
}
```
for more information visits https://getcomposer.org/

Using Git:

Just clone the project inside your extension directory

```
git clone git@github.com:pelmennoteam/yii-fontawesome.git

```
Configuration
=============

In your main config file:

```
...
        'preload' => [
            ...
            'fontawesome',
            ...
        ],
...
 
        // application components
        'components' => [
            'fontawesome' => [
                'class' => 'path.to.fontawesome.FontAwesome',
            ],
        ],
```

Usage
=====

In a view:

```
<i class="fa fa-spinner fa-spin"></i>
<i class="fa fa-refresh fa-spin"></i>
<i class="fa fa-cog fa-spin"></i>
```

Resources
=========

FontAwesome Home Page (http://fortawesome.github.io/Font-Awesome/)

Your feedback is very welcome!

Have Fun!
