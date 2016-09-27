How to create a custom Open Restaurant subtheme.

You can use the Open Restaurant Radix kit as a starting point for your subtheme. Follow the steps below to create a subtheme.

### Requirements

1. [Drush](http://drush.org)
2. [Node](https://nodejs.org)

## Compatibility with Open Restaurant
To make your theme compatible with Open Restaurant, To make your theme compatible with Open Restaurant, add `package: 'Open Restaurant'` to your theme `.info.yml`.

## Create a subtheme

1. Make sure the Radix theme is enabled: `drush en radix -y; drush config-set system.theme default radix -y`.
2. Create a subtheme using the command: `drush radix "SUBTHEME NAME" --kit=https://github.com/openrestaurant/radix-kit-openrestaurant/archive/master.zip`.
3. Go to the root of the subtheme: `cd themes/SUBTHEME_NAME`.
4. Install dependencies: `npm run setup`.
5. Once dependencies are installed, you can activate the new subtheme: `drush en SUBTHEME_NAME -y; drush config-set system.theme default SUBTHEME_NAME -y`.
6. Update the `proxy` config in `themes/SUBTHEME_NAME/config.json`. This is the url of your Open Restaurant site. If your site can be reached at `http://myrestaurant.dev`, set `http://myrestaurant.dev` as the `proxy`.
7. Run `gulp` to watch for changes.
8. You can now start making changes. `gulp` will watch for your `SCSS` changes and automatically inject the styles at `http://localhost:3000`.
