Search API block
================

Provides a search form block in order to show a search input anywhere on your site.

This allows someone to replace the core search form block provided by Search
module which directs the search to those search pages. Instead the search can be
redirected to a View built from a Search API index that contains an exposed filter.

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  <https://backdropcms.org/guide/modules>.
- Add the Search API block to a layout.
- Configure the "Action URL", which will be the path of the search view page. By
  default it will use "/search".
- Configure the "Input name", which will be the name of the exposed filter. By
  default it will use "keys".

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

Maintainers
-----------

- [herbdool](https://github.com/herbdool)
- Seeking additional maintainers.

Credits
-------

Inspired by the search form block in Backdrop core's Search module, Drupal 8+
module [search_api_block](https://www.drupal.org/project/search_api_block), and
by the search block in [search_api_page](https://github.com/backdrop-contrib/search_api_page).
