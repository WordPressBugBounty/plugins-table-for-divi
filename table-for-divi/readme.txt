=== Table for Divi ===
Contributors: wasim98
Tags: table, divi
Requires at least: 4.0.0
Tested up to: 7.1
Stable tag: 2.0.0
Requires PHP: 5.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A quick and easy way to create HTML Table inside the Divi Visual Builder!

== Description ==

**FULLY COMPATIBLE TO DIVI 5**

Table for Divi is a free plugin that provides a Divi table module that can be used to make simple and complex table layouts.


# Requirements

- WordPress (Version 5.0 or higher)
- Divi5 Theme
- Divi5 Builder


# ℹ️ How it works

First, activate the plugin (no configuration needed!)

1. Open up your Visual Builder and click on Plus (+) icon to add new module
2. Select the **Divi Table** module
3. Create new row and add your data to columns


# How to add blank column

To add a blank column in the row just add HTML space entity code `(&nbsp;)` to your column


## How to Update Divi 4 Table Modules to Divi 5

If you are using the previous version of the **Table for Divi** plugin and have upgraded your theme to Divi 5, you will need to update your table modules to ensure full compatibility with Divi 5 functionality.

### Steps to Update

- **Step 1:** Update your theme to Divi 5 and use the built-in Divi 5 migrator to update your default Divi modules.
- **Step 2:** Update the **Table for Divi** plugin to **Version 2.0.0 or higher**, which has been rebuilt from scratch for Divi 5 to provide native support.
- **Step 3:** Navigate to the **Table for Divi** page in the WordPress admin sidebar, click the **'Migrate All Tables to Divi 5'** button, and wait 5–10 seconds depending on your database size.
- **Step 4:** Once you see the success message confirming that all table modules have been successfully migrated to Divi 5, you are ready to use the table module in Divi 5.

**Happy Building!**


== Installation ==

Install the plugin from the WordPress admin page "Plugins > Install"

or

1. Upload `table-for-divi` directory to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress


== Frequently Asked Questions ==

= How much performance does Table for Divi need? =

Actually none! We designed it with maximum page performance in mind. Our tests did show literally no change in page loading speed.

= Is Table for Divi compatible with Caching plugins? =

Yes, absolutely! There is no dynamic logic in the PHP code like other plugins have.

= Is this plugin compatible with every Divi version? =

This plugin is kept compatible with the latest Divi release.

We did test it with all releases since the initial Divi 3.0 release. Possibly it will also work with older versions

= How can I report security bugs? =

You can report security bugs through the Patchstack Vulnerability Disclosure Program. The Patchstack team help validate, triage and handle any security vulnerabilities. [Report a security vulnerability.](https://patchstack.com/database/vdp/table-for-divi)


== Changelog ==

= 2.0.0 =

- Rebuilt **Version 2.0.0** from scratch to support Divi 5 functionality.
- Added an admin page to easily migrate existing tables to Divi 5.

= 1.4.0 =

- Add plugin review functionality

= 1.3.0 =

- Add responsive style for the Divi Table module

= 1.2.0 =

- Added the Dynamic label for the table rows from the content. before, it was the same for all rows which made a problem while editing multiple rows. but now it will pick up the title for the row from the column content.
	
= 1.1.0 =

- Add a Class field for the table row column. (The user can use this field to add different classes to the separate cell)

= 1.0.0 =

- Initial version of the plugin 