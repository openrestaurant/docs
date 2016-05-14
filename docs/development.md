# Development

How to build the development version:

1. Make a directory for your site and go to its root: `mkdir openrestaurant-dev && cd $_`.
2. Clone the openrestaurant repository: `git clone --branch 8.x-2.x arshad@git.drupal.org:project/openrestaurant.git profiles/openrestaurant`
3. Using Drush Make, build the profile: `drush make profiles/openrestaurant/build-openrestaurant.make`
4. Once the build is completed, you can proceed with the [installation](installation).
