=== Advanced Custom Fields - Users Multi-Select Field add-on ===

Contributors: by @lewismcarey (@forepoint)
Tags: acf, acf add-on, users, custom field, user field
Requires at least: 3.0
Tested up to: 3.3.1
Stable tag: 0.0

=== Summary === 

* Generates a user multi-select field filtered by role.
* Stores user data such as name, email and url.
* Associate pages and posts with specific users.

=== Description === 

This is an add-on for the Advanced Custom Fields Wordpress plugin that allows you to add a User field type.

The user field provides the ability to select from a list of your WordPress users, which can be filtered by role. Similar to the post_object type you can allow to be null or select single or multiple values.
The user data stored is an array consisting of the user ID, first name, last name, nice name, display name. email, url, date registered and description.

=== Installation === 

Download the User-Field-ACF-Add-on repo to your theme:

* https://github.com/lewismcarey/User-Field-ACF-Add-on/zipball/master

Register the field - register_field($name, $path)

* register_field(‘Users_field', dirname(__File__) . '/your-ACF-sub-directory/users_field.php');

=== Issues === 

Report any issues or feature requests https://github.com/lewismcarey/User-Field-ACF-Add-on/issues