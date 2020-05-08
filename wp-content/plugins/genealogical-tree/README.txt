=== Genealogical Tree - WordPress Family Tree ===
Contributors: akdevs, freemius
Tags: Family Tree, Genealogy, Ancestry, Family History, GED
Requires at least: 4.4
Tested up to: 5.2
Stable tag: 1.5
License: GPLv2

Genealogical Tree is a ultimate solution for creating and displaying family trees, family history, builds ancestor profiles on WordPress.

== Description ==

Genealogical Tree is a plugin for display family tree. This is a perfect plugin for genealogists and family history enthusiasts to display a family information and tree on your website

== Features  ==
* Display a family tree with unlimited family members.
* 1 Tree Layout
* Drag, zoom in, zoom out for better viewing experience.
* Detect family root automatically.
* Set any member as root with shortcode.
* Add family member information according genealogical method.
* Add life events like - Burial, Adoption, Engagement, Marriage, Divorce and more
* Display family member informations into member page.
* Show all members informations of a family listing page.
* Add Contact Information

== Pro Features ==
* Import Gedcom format (.ged) files.
* 4 Tree layout with many customizable option
* Create unlimited family groups and trees.
* Showing member image into tree.
* Showing member image into member page.
* Support multiple birth and death recored with different source.
* Support multiple spouse, children's will be show separately for each spouse.
* Option to add multiple contact information.
* Option to add multiple life event information.

== Contribute ==

This may have bugs and lack of many features. If you want to contribute on this project, you are more than welcome. Please fork the repository from [Github](https://github.com/akdevsfr/genealogical-tree).

== Documentation ==

* Create a family group.
* Create members under that family group. 
* Make sure you set gender, relationship between members like father, mother , spouse etc.
* Create a page or post to display tree or list of members. Add shortcode into content area.

Use this shortcode to display tree. 

    [gt-tree family='{family-ID}'] Ex: [gt-tree family='1']


bellow are the attributes you can use on shortcode [gt-tree]

- family - Required, Default value - No default value Supported: Family group ID
- root - Optional, Default value - No default value Supported: Member Id
- style - Optional, Default value - '1' Supported: '1'(Free)  '2/3/4' (Pro)
- ajax (Pro) - Optional, Default value - 'false' . Supported: 'false/true' 
- image - Optional, Default value - 'true' . Supported: 'false/true'
- gender - Optional, Default value - 'true' . Supported: 'false/true'
- birt - Optional, Default value - 'true' . Supported: 'false/true'
- deat - Optional, Default value - 'true' . Supported: 'false/true'
- layout - Optional, Default value - 'gt-vr' . Supported: 'gt-vr/gt-hr'
- class - Optional, Default value - No default value Supported: css class


Use this shortcode to display list of trees into a family group. 

    [gt-tree-list family='{family-ID}'] Ex: [gt-tree-list family='1']

You can also add parameter called 'root' 

    [gt-tree family='{family-ID}' root='{member-ID}']  Ex: [gt-tree family='1' root='123'] 

Use this shortcode to display members. 

     [gt-members family='{family-ID}'] Ex: [gt-members family='1']

* family-ID means ID of family f v (Family Group). It is must required parameter.
* member-ID means ID of root member. It is optional parameter.
Details documentation are coming soon.To get any help you direct email to me - akdevs.fr@gmail.com

== Demo ==
Official site is coming soon. 
[AK Devsfr](http://3.19.27.218/web/genealogical-tree/)
[Github](https://github.com/akdevsfr/genealogical-tree)

== Installation ==

Search for “Genealogical Tree” under “Plugins” → “Add New” in your WordPress dashboard to install the plugin.

== Screenshots ==
1. Tree Style 1 Without Image
2. Tree Style 1 With Image
3. Tree Style 1 With Image Horizontal Orientation 
4. Tree Style 2 (Pro) (Support with Image, No image, Horizontal Orientation)
5. Tree Style 3 (Pro) (Support with Image, No image, Horizontal Orientation)
6. Tree Style 4 (Pro) (Support with Image, No image, Horizontal Orientation)
7. Family tree list (Of a single family group) page
8. Member (Individual) page (Front end)
9. Members page (Front end)
10. Member page (Admin area)
11. Multiple birth, death, contact, event record (Pro)
12. Shortcode for each family group
13. Auto generated page with shortcode
14. Import GED (Pro)
15. Import GED Success (Pro)


== Changelog ==

= 1.5.0 - 25 December 2019 =
 * Bug fix
 * New trees
 * Improve tree

= 1.4.0 - 27 September 2019 =
 * Bug fix
 * New tree
 * Improve tree

= 1.3.0 - 29 August 2019 =
* Show birth / death date of father and mother of tree root.
* Add gender icon for siblings.
* Member image size on tree page
* Optimize for find automatic root.
* Hide deleted family. 

= 1.2.0 - 23 August 2019 =
* Rename post type, taxonomy with to avoid other plugin conflict.
* Add ability to multiple birth, death, contact, event record.
* Added new shortcode to display tree list.
* Added tree link into member details.
* Fix display issue on members / member page

 = 1.0.1 - 04 August 2019 =
 * Optimize css and js

 = 1.0.0 - 03 August 2019 =
 * First Release

== Upgrade Notice ==

= 1.5.0 - 25 December 2019 =
 * Bug fix
 * New trees
 * Improve tree

= 1.4.0 - 27 September 2019 =
 * Bug fix
 * New tree
 * Improve tree


= 1.3.0 - 29 August 2019 =
 * Show birth / death date of father and mother of tree root.
 * Add gender icon for siblings.
 * Member image size on tree page
 * Optimize for find automatic root.
 * Hide deleted family. 

= 1.2.0 - 23 August 2019 =
* Rename post type, taxonomy with to avoid other plugin conflict.
* Add ability to multiple birth, death, contact, event record.
* Added new shortcode to display tree list.
* Added tree link into member details.
* Fix display issue on members / member page

= 1.0.1 - 04 August 2019 =
Optimize css and js

= 1.0.0 - 03 August 2019 =
First Release