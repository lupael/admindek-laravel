## Package details


### admindek


### Installation

1. install the package with composer:

```
composer require lupael/admindek-Laravel

```
2. Replace as views

```
php artisan make:admindek

```

3. Publish the public resources by selecting the package-relative command:

```
php artisan vendor:publish

```
4. Add helper in composer.json at project root

```
 "autoload": {
        "psr-4": {
            "App\\": "app/",
        },
        ...
        "files": [
            ...
            "app/Helpers/admindek.php"
        ]
    },

```
