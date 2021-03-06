# WP Subtitle

Subtitle for post type `page`

## Description

This Plugin creates a new input field for subtitles

## Installation

* Put the plugin file in your plugin directory and activate it in your WP backend.
* Go to edit a page
* Below the title you can enter the `subtitle`

## Screenshots

[![Subtitle Meta Box](https://raw.github.com/Horttcore/WordPress-Subtitle/master/screenshot-1.jpg)](https://raw.github.com/Horttcore/WordPress-Subtitle/master/screenshot-1.jpg)

## Frequently Asked Questions

### In which languages is this plugin available

Currently only english and german is supported.

### How can I output my subtitle

There are two functions for subtitles.

`<?php the_subtitle(); ?>`

and

`<?php $title = get_subtitle( $post_id ); ?>`

### Are there any filters I can use?

There is just one filter called `the_subtitle`

### Where can I get support or report bugs?

Please use the [github](https://github.com/Horttcore/WordPress-Subtitle) to report bugs or add feature requests!

### Are there any actions I can hook on?

Sorry no action hooks yet

### I want subtitles for another post type, is this possible?

By default the plugin supports subtitles for posts and pages.
To add support for other custom post types use this WordPress function.
`add_post_type_support( 'YOUR_POST_TYPE', 'subtitle' )`

## Changelog

### 1.3
* Security: Subtitle uses esc_html by default
* `Before` and `after` arguments for `the_subtitle()` template tag
* CSS enhancement

### 1.2
* Bugfix: Subtitle input was displayed even if the post type did not support it

### 1.1
* Enhancement: Code cleanup
* Enhancement: Uninstall process

### 1.0
* Initial release