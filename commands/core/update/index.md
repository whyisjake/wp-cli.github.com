---
layout: default
title: 'wp core update'
---

`wp core update` - Update WordPress.

### OPTIONS

--version=&lt;new_version&gt; [package/zip]
: When passed, updates to new_version, optionally using package/zip as
input.

--force
: Will update even when current WP version &lt; passed version. Use with
caution.

### EXAMPLES

    wp core update

    wp core update --version=3.4 ../latest.zip

    wp core update --version=3.1 --force

