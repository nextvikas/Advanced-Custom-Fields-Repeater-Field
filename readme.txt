=== Advanced Custom Fields: Repeater Field ===

== Installation ==

This software can be treated as both a WP plugin and a theme include.
However, only when activated as a plugin will updates be available/

= Plugin =
1. Copy the 'acf-repeater' folder into your plugins folder
2. Activate the plugin via the Plugins admin page


== Changelog ==

= 2.2.0 =
* Added support for ACF version 6.1.6

= 2.1.0 =
* Added support for ACF version 5.7.0

= 2.0.1 =
* Minor fixes and improvements

= 2.0.0 =
* Added support for ACF version 5

= 1.1.1 =
* Fixed CSS bug causing any nested flexible content fields to not display add/remove buttons for each layout
* Fixes CSS bug causing cropped tables on small screen sizes

= 1.1.0 =
* Added Support for sub field conditional logic
* Added Support for sub field required validation
* Updated UI for 'column width' option (prepend %)
* Updated UI for 'Maximum Rows' option (can be left blank)
* Updated JS to use .on function instead of .live
* Added new update script allowing distribution in premium plugins / themes

= 1.0.1 =
* [Updated] Updated sub field type list to remove 'Tab' as this does not work as a sub field

= 1.0.0 =
* [Updated] Updated update_field parameters
* Official Release

= 0.1.2 =
* [IMPORTANT] This update requires the latest ACF v4 files available on GIT - https://github.com/elliotcondon/acf4
* [Added] Added category to field to appear in the 'Layout' optgroup
* [Updated] Updated dir / path code to use acf filter

= 0.1.1 =
* [IMPORTANT] This update requires the latest ACF v4 files available on GIT - https://github.com/elliotcondon/acf4
* [Updated] Updated naming conventions in field group page

= 0.1.0 =
* [Fixed] Fix wrong str_replace in $dir

= 0.0.9 =
* [Updated] Drop support of old filters / actions

= 0.0.8 =
* [Fixed] Fix bug causing sub fields to not display choices correctly

= 0.0.7 =
* [IMPORTANT] This update requires the latest ACF v4 files available on GIT - https://github.com/elliotcondon/acf4
* [Fixed] Fixed bug where field would appear empty after saving the page. This was caused by a cache conflict which has now been avoided by using the format_value filter to load sub field values instead of load_value

= 0.0.6 =
* [Updated] Update save method to use uniqid for field keys, not pretty field keys

= 0.0.5 =
* [Fixed] Fix wrong css / js urls on WINDOWS server.

= 0.0.4 =
* [Fixed] Fix bug preventing WYSIWYG sub fields to load.

= 0.0.3 =
* [Fixed] Fix load_field hook issues with nested fields.

= 0.0.2 =
* [Fixed] acf_load_field-${parent_hook}-${child_hook} now works!

= 0.0.1 =
* Initial Release.
