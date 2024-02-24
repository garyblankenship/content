---
Image: https://res.cloudinary.com/benjamincrozat-com/image/fetch/c_scale,f_webp,q_auto,w_1200/https://github.com/benjamincrozat/content/assets/3613731/f89fc0a0-564d-498d-aafa-a27292378376
Title: How to publish config files in Laravel 11
Description: The new minimalist application skeleton in Laravel 11 comes with no configuration files. Here's how to publish them.
Canonical:
Audio:
Published at: 2024-02-23
Modified at:
Categories: laravel
---

Starting from Laravel 11, new projects get to experience a slimmer skeleton. Parts of the efforts to make it happen was to numbers of published configuration files which can be overwhelming for new developers. For instance, the cors.php, hashing.php, and view.php files are missing.

That being said, as your application grows, you might need them. Therefore, to publish config files in Laravel 11, use:

```bash
php artisan config:publish
```

Laravel will then ask you to choose which configuration file you want to publish.

And by the way, you can also publish them all at once using:

```bash
php artisan config:publish --all
```