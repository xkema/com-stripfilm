# com-stripfilm

Static site export for [stripfilm.com](https://stripfilm.com/).

## Developer notes

- Use modified and updated local version to continue.
- Find & replace keywords to be aware of: `wpsho`, `placeholder`, `http://`, `offlinezip`, `http://1.gravatar`.
- Remove duplicated `/**/page/1/index.html` paths from pages; `oyuncu`, `stripfilm-tagleri`, `sure`, `tag`, `tur`, `yil`, `yonetmen`.
  - `rm -rf ./*/*/page`
- `dram` category has a second page, add `/page/2/index.html` file to that category manually.
- Remove `index.html` parst of all paths.

## Migration notes

- Updated "about" page. (removed a name)
- Removed contact mails and related text.
- Removed social media buttons.
- All maill accounts are gone.
- Trac removed completely. 

## Tools used

- [All-in-One WP Migration](https://wordpress.org/plugins/all-in-one-wp-migration/)
- [WP2Static](https://wordpress.org/plugins/static-html-output-plugin/)
- [WordPress](https://wordpress.org/plugins/static-html-output-plugin/)
- [Varying Vagrant Vagrants (VVV)](https://varyingvagrantvagrants.org/)

## Removed plugins from original site

- AdSense Booster & Manager (disabled)
- jonradio Private Site (disabled)
- Facebook (was broken)

## Removed themes from original site

- Twenty whatever.

## Other

- Site backups are created with "All-in-One WP Migration" plugins `7.24` version. You can find a copy of the plugin at repo's "assets" directory.