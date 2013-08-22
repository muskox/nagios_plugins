# nagios_plugins

## wordpress_version_check.py

This script checks if you have the latest wordpress version. This script was whipped together quickly to solve my own problem. This script needs a lot of work, noted in the TODOs and Caveats below.

### Caveats

This script only works with themes that tell their version number in the HTML meta data. This works on many themes and I have personally tested the twentyeleven theme.

### TODO

1. Find the canonical place for a Wordpress version, right now it is just scraping the page. 
2. Find the right way to get the wordpress site's version number. Right now this scrapes the version out of the html head meta information.
3. Add better documentation on how to use nagios plugins. Right now only people who already know how they work can use this plugin.
