# ElasticCat


## Installation

- Add the package to your `composer.json` file and run `composer update`:
```json
{
    "require": {
        "argb/elastic-cat": "^1.0"
    }
}
```

- Add the service provider to your `config/app.php` file, inside the `providers` array: `'Argb\ElasticCat\BouncyServiceProvider'`

- Publish the config file by running the following command in the terminal: `php artisan vendor:publish`

- Edit the config files: `config/bouncy.php` for Bouncy specific options and `config/elasticsearch.php` for configuring the ElasticSearch client.
