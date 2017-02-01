# Development

### How to install a contrib module

1. Go to the root of your Open Restaurant project. The root of the project is one level from the `web` directory.
2. Use composer to install the module as follows: `composer require drupal/google_analytics`.

Composer will download and place the module inside the `web/modules/contrib` directory.

You can now go to **Extend** to enable the module or use `drush en google_analytics`.
