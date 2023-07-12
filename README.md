# Font-Awesome Icon Set
This bundle allows you to use Font Awesome Free icons as themes extension in map.apps. All available icons can be seen here: http://fortawesome.github.io/Font-Awesome/icons/

After installing the bundle to your map.apps installation and adding it to your app you can use the new icons by adding e.g. “iconClass”:”fa-binoculars” to a tool definition inside the app.json. Or, if you have your own custom theme, you can replace all of the map.apps default icons.

### Sample App ###
https://demos.conterra.de/mapapps/resources/apps/downloads_fontawesome

![Screensot of sample](https://github.com/conterra/mapapps-fontawesome/blob/master/screenshot.JPG)


## :warning: Updating from Font Awesome smaller than 5.0.0  :warning: ##

Font Awesome provides an even larger variation of icons with the 5.0.0 release. Please have a look at [the Font Awesome Documentation](https://fontawesome.com/how-to-use/svg-with-js) for detailed information.
### In short ###
In case you have used a previous version of the bundle dn_fontawesome it is needed to add a prefix to your icon class otherwise the icons will not appear.
Example: "iconClass": "fa-truck" will become "iconClass": "fas fa-truck". Where "fas" stand for "fontawesome-solid".

With 5.0.0 the following variations are available:

* far - fontawesome regular
* fas - fontawesome solid
* fab - fontawesome brands
