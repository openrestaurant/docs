# Theming

How to create a custom Open Restaurant subtheme.

You can use the Open Restaurant Radix kit as a starting point for your subtheme. Follow the steps below to create the subtheme.

### Dependencies

1. [Drush](http://drush.org)
2. [Node](https://nodejs.org)

## Steps

1. Make sure the Radix theme is enabled: `drush en radix -y; drush config-set system.theme default radix -y`.
2. Create a subtheme using the command: `drush radix SUBTHEME_NAME --kit=https://github.com/openrestaurant/radix-kit-openrestaurant/archive/master.zip`.
3. Go to the root of the subtheme: `cd themes/SUBTHEME_DIRECTORY`.
4. Install dependencies: `npm run setup`.
5. Once dependencies are installed, you can activate the new subtheme: `drush en SUBTHEME_NAME -y; drush config-set system.theme default SUBTHEME_NAME -y`.
6. Update the `proxy` config in `themes/SUBTHEME_DIRECTORY/config.json`. This is the url of your Open Restaurant site. If your site can be reached at `http://myrestaurant.dev`, set `http://myrestaurant.dev` as the `proxy`.
7. Run `gulp` to watch for changes.
8. You can now start making changes. `Gulp` will watch for your `SCSS` changes and automatically inject the styles at `http://localhost:3000`.
