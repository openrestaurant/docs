# Translation

Open Restaurant has built in support for multilingual. Follow the guides below to add a new language to your site and learn how to
translate content.

### Step 1: Enable the Translation module.

<div class="admonition note">
<p class="first admonition-title">Note</p>
<p class="last">The Translation module is available as from version `2.2.0`.</p>
</div>

To get started we need to enable a few modules and add a new language:

Enable the Translation module under Open Restaurant at `/admin/modules`. This will install the required multilingual dependencies
and set up a few default configuration.

<img width="675" alt="Translation module" src="https://cloud.githubusercontent.com/assets/124599/22478910/45fb2c12-e805-11e6-9f63-fd51e88a550b.png">

### Step 2: Add languages

Once the Translation module is enabled, go to Configuration ⟶ Regional and language ⟶ Languages (`/admin/config/regional/language`) and click on `+ Add language` to add a new language.

<img width="675" alt="Add language" src="https://cloud.githubusercontent.com/assets/124599/22478846/13e04c3a-e805-11e6-9222-500ed5d00dba.png">

Once the language is imported, go to Configuration ⟶ Regional and language ⟶ Content language and click save.

### Translate the site name and slogan

1. Go to Configuration ⟶ Regional and language ⟶ Configuration translation (`/admin/config/regional/config-translation`).
2. Click on translate next to **System information**.
3. Click on Edit next to the language you wish to translate to.
4. Translate the site name and slogan.
5. Click on Save translation.

### Translate the main navigation and other navigations.

1. Go to Structure ⟶ Navigation ⟶ Main navigation (`/admin/structure/menu/manage/main`).
2. To translate custom menu links such as Home and Contact, click on the dropdown under *Operations* and click on *Translate*.
3. To translate menu links provided by views such as Menu, Hours & Locations, Blog and Events, see the *Translate the views* section below.

<img width="675" alt="Translate custom menu links" src="https://cloud.githubusercontent.com/assets/124599/22480767/fb0077c4-e80b-11e6-9433-8981d6caa4d0.png">

### Translate the hero and blocks

1. Go to Structure ⟶ Block Layout ⟶ Custom block library (`/admin/structure/block/block-content`).
2. Find the block you need to translate, click on the dropdown under *Operations* and click on *Translate*.
3. Click on **Add** next to the language.
4. Translate the block by adding values for the fields.
5. Make sure the translation is published by expanding the Translation fieldset and checking *This translation is published*. 
6. Click on Save.

### Translate the taxonomy terms: menu categories and nutrition types.

1. Go to Structure ⟶ Taxonomy ⟶ Menu category (`/admin/structure/taxonomy/manage/menu_category/overview`).
2. Find the category you need to translate, click on the dropdown under *Operations* and click on *Translate*.
3. Click on **Add** next to the language.
4. Translate the category by filling the translated values in the fields provided.
5. Make sure the translation is published by expanding the Translation fieldset and checking *This translation is published*.
6. Click on Save.

### Translate the content: menu, blog posts, events and locations.

1. Go to Content ⟶ Menus.
2. Find the menu you need to translate, click on the dropdown under *Operations* and click on *Translate*.
3. Click on **Add** next to the language.
4. Translate the menu by filling the translated values in the fields. You can also upload a different image for the translated menu.
5. Click on Save and Publish.

Follow the same steps as above to translate the blog posts, events and locations.

### Translate the views: links in main navigation, featured events, news and blogs.

Most of the content inside these views are handled by translation the content as shown above. Follow the steps below to translate the header and footer text. We will use the Featured blog post as an example.

1. Go to Configuration ⟶ Regional and language ⟶ Configuration translation (`/admin/config/regional/config-translation`).
2. Click on **List** next to **View**.
3. Click on **Translate** next to the **Blog Posts**.
4. Click on **Edit** next to the language.
5. To translate the menu link, expand Displays ⟶ Page Display settings ⟶ Page display options ⟶ Menu.
6. Add the menu title under the title field.
7. To translate the Featured blog post header and footer text, expand Displays ⟶ Featured blog posts Display settings ⟶ Featured Blog Posts Block display options.
8. Add translated header and footer text to the fields provided on the right.
9. Save.
