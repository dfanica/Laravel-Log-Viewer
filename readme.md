# Log Viewer

A simple bundle to display your Laravel 3 log files.

If you are using Laravel 4 please look at this repo: 
https://github.com/mikemand/logviewer


## Installation

1. run this cmd in yout laravel root
```bsh
php artisan bundle:install laravel-logviewer
```

2. copy or move the /budble/logviewer/public/logviewer.css file to your actually public directory


3. Add this to your application/bundles.php file:

```php
return array(

	'logviewer' => array(
		'location' => 'logviewer',
		'handles' => 'logviewer'
	)

);
```

