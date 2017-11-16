rss-roller
==========

Shell script for generating and updating rss feeds. It allows you to configure and build rss feeds
for different local sources.

## Usage:

Run without parameters: start in 'create feed config' mode.  In this mode it will ask few questions
and write configuration file for your feed in _.rss-roller_ directory under user home directory.

**rss-roller**

To see what feeds are configured run with -l flag - the code will list all configuratiopn files in
_.rss-roller_ directory.

**rss-roller -l**

To build feed run with _-c feedconfigname_ where **feedconfigname** is a name of the existing feed
configuration under _.rss-roller_ directory.

**rss-roller -c feedconfigname**

## ToDo:

- Allow building feeds recursively from a source directory three
- Validate user input in 'create feed config' mode.
- Edit feed config mode.
- Clear bash source code and make it [GSSG](https://google.github.io/styleguide/shell.xml)
  compliant.

## Credits:

Based on [Max Hebditch](http://maxhebditch.co.uk/)
[rss-roller](https://github.com/maxhebditch/rss-roller) script. It is worthwhile checking that the
rss feed created is valid using an [online tool](http://validator.w3.org/feed/) if the rss file
generated doesn't work as expected.
