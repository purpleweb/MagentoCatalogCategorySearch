README
================

This plugin is the Magento Catalog Category Search plugin from ISAAC's GEEKYPLUGINS.

Original page : http://www.geekyplugins.com/magento/catalog-category-search.dot

The ISAAC Catalog Category Search extension allows users to search within a category or subcategory, by adding a drop-down list to the quick search bar. As an aid to the user, the active category is automatically selected in the drop-down list.

Features
--------

The quick search bar is extended with a drop-down list containing the main categories and optionally its subcategories. After selecting a category, entering the search query, and pressing the search button (or enter), the search result page is shown for the search query where the results are filtered by the selected category. On this page and on category pages, the active category (filter or current category) is also selected in the drop-down list to avoid the extra selection step.
The following options can be configured:

* Select categories on category pages (default ‘yes’): indicates if the active category on a category page is automatically selected in the drop-down list. The active category is determined by the active category filter and, as a fallback by the current category).
* Show subcategories (default ‘yes’): indicates whether subcategories should be displayed in the category drop-down list.
* Subcategory indentation (default ‘> ’): the indentation text that is shown in front of each subcategory in the category drop-down list.

Requirements
------------

Compatible with the following Magento versions: 1.4.1, 1.4.2, 1.5.0, 1.5.1, 1.6.1, 1.6.2, 1.7.0.2

Translations
------------

Translations include English, Dutch and French

Install via Modman
----------------

You can install this module using [Colin Mollenhour's](https://github.com/colinmollenhour) [Modman tool](https://github.com/colinmollenhour/modman)

```bash
$ modman init
$ modman clone https://github.com/tonioMtl/MagentoCatalogCategorySearch.git
```
You can update the module with this command

```bash
$ modman update MagentoCatalogCategorySearch
```