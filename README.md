# Introduction
As request, we should do in Laravel. But because we need to do API only, so I decide to do it with Lumen. Hope it can be acceptable.

I use [jwt-token](https://github.com/tymondesigns/jwt-auth) for token base authentication in Lumen.

# Setup project

1.  `cp .env.example .env`
2. Update database name, database user your host
3. ` composer install `
4. ` php artisan migrate --seed`
5. ` php artisan jwt:secret`

# Run test demo
`vendor/bin/phpunit `
