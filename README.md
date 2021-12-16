# articles API

> Laravel API that uses the API resources. This is an API for an article CRUD app

## Quick Start

``` bash
# Install Dependencies
composer install

# Run Migrations
php artisan migrate

# Import Articles
php artisan db:seed

# If you get an error about an encryption key
php artisan key:generate
```

## Endpoints

### List all articles with links and meta
``` bash
GET
api/articles
```
### Get single article
``` bash
GET
api/articles/{article}
```

### Delete article
``` bash
DELETE
api/articles/{article}
```

### Add article
``` bash
POST
api/articles
```

### Update article
``` bash
PUT/PATCH
api/articles/{article}
```
