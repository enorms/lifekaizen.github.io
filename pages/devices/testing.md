---
layout: default

# use directory structure under pages
# example:
# ./pages/devices/testing.md -> http://127.0.0.1:4000/devices/testing.html
#                               http://127.0.0.1:4000/devices/

permalink: /devices/testing
---

TESTING does this go?

Site wide information + configuration settings from \_config.yml. See below for details.

<!-- site: {{site}} -->

Page specific information + the front matter. Custom variables set via the front matter will be available here. See below for details.

<!-- page: {{page}} -->

Layout specific information + the front matter. Custom variables set via front matter in layouts will be available here.

<!-- layout: {{layout}} -->

In layout files, the rendered content of the Post or Page being wrapped. Not defined in Post or Page files.

<!-- content: {{content}} -->

The current time (when you run the jekyll command).

<!-- site.time: {{site.time}} -->

A list of all Pages.

<!-- site.pages: {{site.pages}} -->

A reverse chronological list of all Posts.

<!-- site.posts -->

If the page being processed is a Post, this contains a list of up to ten related Posts. By default, these are the ten most recent posts. For high quality but slow to compute results, run the jekyll command with the --lsi (latent semantic indexing) option. Also note GitHub Pages does not support the lsi option when generating sites.

<!-- site.related_posts -->

A list of all static files (i.e. files not processed by Jekyll's converters or the Liquid renderer). Each file has five properties: path, modified_time, name, basename and extname.

<!-- site.static_files: {{site.static_files}} -->

A subset of site.pages listing those which end in .html.

<!-- site.html_pages -->

A subset of site.static_files listing those which end in .html.

<!-- site.html_files -->

A list of all the collections (including posts).

<!-- site.collections: {{site.collections}} -->

A list containing the data loaded from the YAML files located in the \_data directory.

<!-- site.data: {{site.data}} -->

A list of all the documents in every collection.

<!-- site.documents: {{site.documents}} -->

The list of all Posts in category CATEGORY.

<!-- site.categories.CATEGORY -->

The list of all Posts with tag TAG.

<!-- site.tags.TAG -->

Contains the url of your site as it is configured in the \_config.yml. For example, if you have url: http://mysite.com in your configuration file, then it will be accessible in Liquid as site.url. For the development environment there is an exception, if you are running jekyll serve in a development environment site.url will be set to the value of host, port, and SSL-related options. This defaults to url: http://localhost:4000.

<!-- site.url -->

All the variables set via the command line and your \_config.yml are available through the site variable. For example, if you have foo: bar in your configuration file, then it will be accessible in Liquid as site.foo. Jekyll does not parse changes to \_config.yml in watch mode, you must restart Jekyll to see changes to variables.

<!-- site.[CONFIGURATION_DATA] -->
