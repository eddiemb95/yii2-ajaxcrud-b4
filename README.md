yii2-ajaxcrud-b4 
=============



[![Latest Stable Version](https://poser.pugx.org/eddiemb95/yii2-ajaxcrud/v/stable)](https://packagist.org/packages/eddiemb95/yii2-ajaxcrud)
[![License](https://poser.pugx.org/eddiemb95/yii2-ajaxcrud/license)](https://packagist.org/packages/eddiemb95/yii2-ajaxcrud)
[![Total Downloads](https://poser.pugx.org/eddiemb95/yii2-ajaxcrud/downloads)](https://packagist.org/packages/eddiemb95/yii2-ajaxcrud)

Gii CRUD template for Single Page Ajax Administration for yii2 para boopstrap 4 


Features
------------
+ Create, read, update, delete in onpage with Ajax
+ Bulk delete suport
+ Pjax widget suport
+ Export function(pdf,html,text,csv,excel,json)

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist eddiemb65/yii2-ajaxcrud-b4 "*"
```

or add

```
"eddiemb65/yii2-ajaxcrud-b4": "*"
```

to the require section of your `composer.json` file.


Usage
-----
For first you must enable Gii module Read more about [Gii code generation tool](http://www.yiiframework.com/doc-2.0/guide-tool-gii.html)

Because this extension used [kartik-v/yii2-grid](https://github.com/kartik-v/yii2-grid) extensions so we must config gridview module before

Let 's add into modules config in your main config file
````php
'modules' => [
    'gridview' =>  [
        'class' => '\kartik\grid\Module'
    ]       
]
````

You can then access Gii through the following URL:

http://localhost/path/to/index.php?r=gii

and you can see <b>Ajax CRUD Generator</b>

Other Links

