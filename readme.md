#What is microajax?
One of the smallest and easiest AJAX libraries
##Usage:
```js
microAjax("/resource/url", function (res) { alert (res); });
```


#FAQ
####1. How can I detect an AJAX request in my server-side scripts?

Like mootools and prototype, microajax sets the X-Requested-With header to XMLHttpRequest. This should be easy to detect.

**PHP:** 
```php
if ($_SERVER['X-Requested-With'] == 'XMLHttpRequest') { // do something clever } 
```
