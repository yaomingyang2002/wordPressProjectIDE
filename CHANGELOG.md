
# CHANGELOG

## Head (1.7.6) | 15.11.2016
* fixed a bug that occurred when sending the admin email after core installation
* fixed a bug that occurred on installing a theme from Github using the current version of WP-CLI (0.25.0)
* add option to define WordPress Version
* documentation updates
* add rewrite flush to make sure permalinks are working correctly
* add firstname/lastname to default user

Contributors: @flurinduerst, @ShaneShipston

## 1.7.1 | 02.08.2016
* fixed a bug that caused an error if a theme was installed that doesn't end with `master.zip`
* add additional options
  * custom page to be used as front_page
  * timezone
  * description
  * default image sizes
* add settings setup task
* small bugfixes
* cleanup/renaming

## 1.6.1 | 07.07.2016
* bugfix (now correctly checking `theme_rename`)
* add error handler that asks the user to continue if an error occured
* add google-sitemap-generator to preset plugins
* remove dublicated plugin entry
* remove WPDistillery Version from config/setup - remain at README

## 1.5.1 | 21.06.2016
* Rename to WP Distillery
* Bugfixes / Typo / Documentation

## 1.4.0 | 17.06.2016
* Add support for custom WP root folder
* Add option to rename theme after installation
* Add file versions to config.yml and setup.sh
* Fix Typo in setup procedure


## 1.3.0 | 16.06.2016
* Add modular setup task options

## 1.2.0 | 17.06.2016
* Public Release
