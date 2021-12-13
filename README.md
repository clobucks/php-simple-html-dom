php-simple-html-dom-parser
==========================

Version 1.5.2

Adaptation for Composer and PSR-0 of:

A HTML DOM parser written in PHP5+ let you manipulate HTML in a very easy way!
Require PHP 5+.
Supports invalid HTML.
Find tags on an HTML page with selectors just like jQuery.
Extract contents from HTML in a single line.

Fixed for php 7+

http://simplehtmldom.sourceforge.net/


Install
-------

 composer.phar
```json
"require": {
    "enemis/php-simple-html-dom-parser": "1.5.2"
    }
```

Usage
-----

```php
use Enemis\PhpSimpleHtmlDom;

...
$dom = HtmlDomParser::str_get_html( $str );
or 
$dom = HtmlDomParser::file_get_html( $file_name );

$elems = $dom->find($elem_name);
...

```
