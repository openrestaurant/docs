# Requirements

**Database**
MySQL 5.5.3/MariaDB 5.5.20/Percona Server 5.5.8 or higher with PDO and an InnoDB-compatible primary storage engine.

**PHP**
PHP 5.5.9 or higher (PHP 7+ recommended)

# Installation

We highly recommend using [Composer](http://getcomposer.org) to install your Open Restaurant codebase.

#### Step 1: Add packages.drupal.org repository:

```
composer config repositories.drupal composer https://packages.drupal.org/8
```

#### Step 2: Use the following command to create a new Open Restaurant project:

```
composer create-project openrestaurant/openrestaurant-project myrestaurant
```

Composer will pull in the openrestaurant profile and all required dependencies. A **web** directory will be created and the Drupal code will be placed there. You can then install it like you would any other Drupal site.
