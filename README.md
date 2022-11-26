
This is an extensively modified version of Patrick Marsceill's [Just the Docs](https://github.com/just-the-docs/just-the-docs) Jekyll theme.

I've heavily modified it, both to make it more suited for my purposes,
and as a learning experience.

## Header Arguments:

parent: Title of Parent
: Nest this page with the title "Title of Parent" in the navigation menus. Note that unlike the original Jekyll, I don't check for grand_parent title. (Maybe I should check the grandparent if one is present.)
has_toc: false
: Parent pages usually list their children after the main content. This disables that automatically generated list of children.
date and last_modified_date
: Self explanatory. Use YYYY-MM-DD format.
layout: post
: Use the layout with my additions, namely: ToC, subtitle, date in header.
toc: true
: My addition which adds a collapsible table of contents to the page, using [jekyll-toc](https://github.com/toshimaru/jekyll-toc). Only works with `layout: post`.
