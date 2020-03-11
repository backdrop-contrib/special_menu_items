Special Menu Items Module
=========================

Description
-----------
Special Menu Items is a module that enables "placeholder" and "separator" menu
items. A placeholder is a menu item which is actually not a link. Something like 
this is useful with drop down menus where the goal is to have a parent link
which is actually not linking to a page, but which is just acting as a parent,
grouping some children below it. A separator menu item is something like
"------" which is also not linking anywhere but merely a way to structure menus.

This module depends on the core Menu module. It is meant to be used with
drop-down menus (introduced in core after Backdrop 1.5.0), or you will not be
able to acess children of nolink menu items.

Features
--------
  - User can create a new menu item and place either `<nolink>` or `<separator>`
    in the Path field (without quotes).
  - When the menu is rendered any `<nolink>` item will be rendered similar to a 
    normal menu link item, but there will be no link, just the title. Since
    version 1.3 you can change the HTML tag used for the menu item.
  - When the menu is rendered any `<separator>` item will be rendered as an item 
    which has no link, and the default title will be "-------". Since version
    1.3 it is possible to change both the HTML tag and the title.
  - Breadcrumb of `<nolink>` will be rendered same as `<nolink>` menu item.
  - A "nolink" CSS class is added to `<nolink>` menu items.
  - A "seperator" CSS class is added to `<seperator>` menu items.

Installation
------------
1. Copy the special_menu_items folder to your /modules directory.
2. Go to Administration -> Functionality -> Modules (admin/modules) and enable
   the module.
3. Configure the module settings at Administration -> System -> Special Menu
   Items (admin/config/system/special_menu_items).

Upgrading
---------
Just overwrite (or replace) the older special_menu_items folder with the newer 
version.

LICENSE
---------------    

This project is GPL v2 software. See the LICENSE.txt file in this directory 
for complete text.

CURRENT MAINTAINERS
---------------    

 - [Laryn Kragt Bakker](https://github.com/laryn) - [CEDC.org](https://cedc.org)

CREDITS   
--------------- 

 - Ported to Backdrop CMS by [docwilmot](https://github.com/docwilmot)
 - This module is a fork of the Drupal version developed by [Servit Open Source 
Solutions](http://servit.ch) and maintained by [Khaled Zaidan](mailto:zaidan@servit.ch)
 - Written by Tamir Al Zoubi and Karim Djelid - [Servit Open Source Solutions](http://www.servit.ch)
