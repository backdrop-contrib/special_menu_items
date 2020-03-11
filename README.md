# Special Menu Items

This module enables "placeholder" and "separator" menu items. 

A **placeholder** is a menu item which is actually not a link. Something like 
this is useful with drop down menus where the goal is to have a parent link
which is actually not linking to a page, but which is just acting as a parent,
grouping some children below it. 

A **separator** menu item is something like "------" which is also not linked
to anything but is merely a way to structure menus.

This module depends on the core Menu module.

## Configuration and Usage

  - Configure settings at **Administration > System > Special Menu Items** 
    (`admin/config/system/special_menu_items`).

  - A user can create a new menu item and place either `<nolink>` or 
    `<separator>` in the Path field.
  - When the menu is rendered any `<nolink>` item will show similarly to a 
    normal menu link item, but there will be no link added to the title. You
    can change the HTML tag used for the menu item in the module configuration.
  - When the menu is rendered any `<separator>` item will show as an item 
    which has no link, and the default title will be "-------". You
    can change the HTML tag and title used for the menu item in the module
    configuration.
  - A breadcrumb of `<nolink>` will be rendered the same as a `<nolink>` menu
    item.
  - A `nolink` CSS class is added to `<nolink>` menu items.
  - A `separator` CSS class is added to `<separator>` menu items.
  
  - View and edit more instructions in the 
    [Wiki](https://github.com/backdrop-contrib/special_menu_items/wiki).

## Installation

 - Install this module and its dependencies using the official 
  [Backdrop CMS instructions](https://backdropcms.org/guide/modules)

## Issues

Bugs and Feature requests should be reported in the 
[Issue Queue](https://github.com/backdrop-contrib/special_menu_items/issues)

## Current Maintainers

 - [Laryn Kragt Bakker](https://github.com/laryn) - [CEDC.org](https://cedc.org)

## Credits

 - Ported to Backdrop CMS by [docwilmot](https://github.com/docwilmot)
 - Originally developed for Drupal 7 by Tamir Al Zoubi and Karim Djelid 
   ([Servit Open Source Solutions](http://servit.ch)) and maintained by 
   [Simon Perdrisat (gagarine)](https://www.drupal.org/u/gagarine).

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
