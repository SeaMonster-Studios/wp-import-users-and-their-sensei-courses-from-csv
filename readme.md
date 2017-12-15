=== Import Users and their Sensei Courses from CSV ===
Contributors: SeaMonster Studios, carazo, hornero
Tags: csv, sensei, courses, import, importer, meta data, meta, user, users, user meta,  editor, profile, custom, fields, delimiter, update, insert
Requires at least: 3.4
Tested up to: 4.9
Stable tag: 1.10.8.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A plugin to import users using CSV files to WP database automatically including custom user meta

== Description ==

Clean and easy-to-use Import users plugin. It includes custom user meta to be included automatically from a CSV file and delimitation auto-detector. It also is able to send a mail to each user imported and all the meta data imported is ready to edit into user profile.

*	Import CSV file with users directly to your WordPress
*	Import thousends of users in only some seconds
*	You can also import meta-data like data from WooCommerce customers using the correct meta_keys
*	Send a mail to every new user
*	Use your own 
*	You can also update data of each user
*	Assing a role
*	Create a cron task to import users periodically
*	Edit the metadata (you will be able to edit the metadata imported using metakeys directly in the profile of each user)
*	Read our documentation
*	Ask anything in support forum, we try to give the best support

In Codection we have more plugins, please take a look to them.

*	[RedSys Gateway for WooCommerce Pro a plugin to connect your WooCommerce to RedSys](http://codection.com/producto/redsys-gateway-for-woocommerce) (premium)
*	[Ceca Gateway for WooCommerce Pro a plugin to connect your WooCommerce to Ceca](http://codection.com/producto/ceca-gateway-for-woocommerce-pro/) (premium)
*	[BBVA Bancomer for WooCommerce Pro a plugin to connect your WooCommerce to BBVA Bancomer](http://codection.com/producto/bbva-bancomer-mexico-gateway-for-woocommerce-pro/) (premium)
*	[RedSys Button for WordPress a plugin to receive payments using RedSys in WordPress without using WooCommerce](http://codection.com/producto/redsys-button-wordpress/) (premium)
*	[Clean Login a plugin to create your own register, log in, lost password and update profile forms](https://wordpress.org/plugins/clean-login/) (free)

## **Basics**

*   Import users from a CSV easily, along with their respective Sensei courses
*   And also extra profile information with the user meta data (included in the CSV with your custom fields)
*   Just upload the CSV file (one included as example)
*   All your users will be created/updated with the updated information, and of course including the user meta
*   Autodetect delimiter compatible with `comma , `, `semicolon ; ` and `bar | `

## **Usage**

Once the plugin is installed you can use it. Go to Tools menu and there, there will be a section called _Insert users from CSV_. Just choose your CSV file and go!

### **CSV generation**

You can generate CSV file with all users inside it, using a standar spreadsheet software like: Microsoft Excel, LibreOffice Calc, OpenOffice Calc or Gnumeric.

You have to create the file filled with information (or take it from another database) and you will only have to choose CSV file when you "Save as..." the file. As example, a CSV file is included with the plugin.

### **Some considerations**

Plugin will automatically detect:

* Charset and set it to **UTF-8** to prevent problems with non-ASCII characters.
* It also will **auto detect line-ending** to prevent problems with different OS.
* Finally, it will **detect the delimiter** being used in CSV file ("," or ";" or "|")

== Example Screenshot ==
![](https://github.com/SeaMonster-Studios/wp-import-users-and-their-sensei-courses-from-csv/blob/master/csv_example.png)

== Installation ==

### **Installation**

*   Install **Import Users and their Sensei Courses from CSV** automatically through the WordPress Dashboard or by uploading the ZIP file in the _plugins_ directory.
*   Then, after the package is uploaded and extracted, click&nbsp;_Activate Plugin_.

Now going through the points above, you should now see a new&nbsp;_Import Users, Sensei Courses from CSV_&nbsp;menu item under Tool menu in the sidebar of the admin panel, see figure below of how it looks like.

If you get any error after following through the steps above please contact us through item support comments so we can get back to you with possible helps in installing the plugin and more.

Please read documentation before start using this plugin.
