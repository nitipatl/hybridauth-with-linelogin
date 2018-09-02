# [HybridAuth](https://github.com/hybridauth/hybridauth) + Line Login provider

## Goal
User can login to our system by Line account.

## Manual

- Install locally composer `curl -sS https://getcomposer.org/installer | php` 

- Install packages via composer `php composer.phar install` 

- move a file `Line.php` to folder `vendor/hybridauth/hybridauth/src/Provider/`

- Config `id` and `secret` values in `index.php` from [this tutorial](https://developers.line.me/en/docs/line-login/getting-started)

## References
- https://developers.line.me/en/docs/line-login/web/integrate-line-login/