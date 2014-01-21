WP-Easy-Post-Types
==================

Create custom WordPress post types on the fly with an easy to use interface. Then manage custom fields and categories for your post types.

## Description

This plugin lets you take advantage of the Wordpress 3.0 custom post type feature, and create your own post type. The plugin allows you to add a set of fields attached to your new post type, so that in the edit and add new windows a new box will show with the fields defined. Each field added will be saved in the Wordpress Database as a custom field, so that you can take advantage of the standard Wordpress query rules to list your content on the page template.

[Plugin Website](http://www.wpeasyposttypes.com)

## Installation

1. After downloading the plugin, unzip the plugin
1. Upload `easyposttypes` to the `/wp-content/plugins/` directory  or go through the Wordpress plugin Upload dialog
1. Activate the plugin

## Frequently Asked Questions

1. Where can I learn more about Easy Post Types?
To learn more, please visit http://www.wpeasyposttypes.com

2. I get a 404 page when trying to view a post of my custom post type

This can be caused by having a page with the same slug as your custom post type key. The Page does not need to be published (it can event be in the trash) for this issue to exists.

You will either need to permanently delete the Page or create the a new post type with a different key.

This is an issue with WordPress rewrite.


## Screenshots

1. screenshot-1.jpg is the add post type dialog.

2. screenshot-2.jpg is the add field dialog.

3. screenshot-3.jpg are the import/export features.

## Changelog

### 1.0B
1. The initial release

### 1.0.1B

1. The permalinks are automatically updated now resolving the issue of having to manually update them from the options page to get URLs to work for new post types
2. A custom admin icon instead of the standard gear icon
3. An improved UX workflow for adding new post type

### 1.2.0

1. Added more styling for better UI on the administration interface
2. Added more classes for custom components
3. Added the ability to create a custom taxonomy and associate that with the normal Posts and Pages.
4. Fixed a few issues with the Javascript on front end side
5. Fixed URLs and local paths known issues
6. Improved the browse images functionality
7. Fixed permalink issues for archive pages

### 1.2.1
1. Last updated time on WP Site

### 1.3.0
1. Javascript and styles are loaded only on the admin side when needed
2. Reference field improved with search enabled
3. Textfield have WYSIWYG editor and language support for qTranslate
4. Other bug and improvement fixes

### 1.3.1
1. Fixed a warning on custom taxonomy
2. Fixed checkbox class ID error

### 1.4.0
1. Fixed issues with category save functionality

### 1.4.1
1. Updated jQuery method to support jQuery version >= 1.9: switched calls to live() to on()

### 1.4.2
1. Update to fix bug in display of custom fields in admin menus

### 1.4.3
1. Fix bug related to display of custom text field value

### 1.4.4
1. Fix bug related to image URL sanitization
