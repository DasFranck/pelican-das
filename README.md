Pelican-das
==============

A minimal theme for [Pelican](http://blog.getpelican.com/) that uses uikit and based on the [Pelican-mg](https://github.com/lucachr/pelican-mg) theme.  
The theme is suited for a single/multi author blog without tag pages nor blogroll. Feeds are provided via ATOM.

Live Example
--------------
Check out [my blog](http://dasfranck.fr).

Features
--------------

* [Open Graph](http://ogp.me) support.
* [Twitter Summary Card](https://dev.twitter.com/cards/types/summary) support.
* [Schema.org](http://schema.org) support.
* Search with [Tipue Search](http://www.tipue.com/search).
* Responsive design.
* SCSS style sheets.
* Analytics with Google Analytics, PIWIK and StatCounter.
* Share buttons built with share urls.
* Custom footer notice.

Settings
--------------

The following settings are required for a correct behaviour of this theme.

```python
    TAG_SAVE_AS = ''
    AUTHOR_SAVE_AS = ''
    DIRECT_TEMPLATES = ('index', 'categories', 'archives', 'search', 'tipue_search')
    TIPUE_SEARCH_SAVE_AS = 'tipue_search.json'
```

###Optional settings

**ALT_NAME**  
An alternative name for your site. It appears in the header bar.

**DESCRIPTION**  
A brief description of your site, for social networks and search engines.

**FAVICON**  
The relative path of your favicon, this is needed for Disqus forum favicon.

**FAVICON_TYPE**  
The MIME type of your favicon, this is needed for Disqus forum favicon.

**FOOTER**  
A custom footer notice.

**META_IMAGE**  
The absolute URL of a custom image for the `og:image` meta property, Twitter 
summary card, and `image` meta property of Schema.org. This image is used in 
every page of the blog. Articles and pages can override the default 
**META_IMAGE** by setting the "image" metadata in the relative file.  

**META_IMAGE_TYPE**  
The MIME type for **META_IMAGE**, this is needed for `og:image:type`.

**SC_PROJECT**   
The StatCounter project number.  

**SC_SECURITY**   
The StatCounter security code for the project.

**SHARE**  
Enable share buttons, boolean.

**SOCIAL**  
A list of tuples (icon, URL). The icons are from [Font Awesome]
(http://fortawesome.github.io/Font-Awesome/). The suffix "-square" is removed 
in the footer icons of the small screen layout.   
e.g.   
```python
    SOCIAL = (('twitter', 'https://twitter.com/luca_chr'),
              ('google-plus-square', 'https://plus.google.com/117284397605208270870'),
              ('github', 'https://github.com/lucachr'),
              ('envelope', 'mailto:luca92web@gmail.com'),)
```

License
---------

Pelican-das is released under [the MIT License](http://opensource.org/licenses/MIT).
