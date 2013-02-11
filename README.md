# Fresh: a responsive Pelican theme that uses HTML5

Fresh is a [Pelican](http://getpelican.com) theme with clean layout.
This theme uses HTML5 and its layout is responsive -- thanks to Smashing HTML5 and Twitter Bootstrap.

## Features

*   Google Analytics
*   DISQUS comment system
*   Custom link lists
*   Social widgets
*   "Fork me on GitHub" ribbon
*   **Google Custom Search Engine** -- you can use this as your search bar!
*   **Hide categories from menu**
*   Syntax highlighting for code blocks

## Settings

### Built-in Global Variables

The theme supports most Pelican built-in global variables, and some of them are listed below.

*   `GOOGLE_ANALYTICS`
*   `DISQUS_SITENAME`
*   `LINKS (('name1', 'url1'), ('name2', 'url2'))`
*   `SOCIAL (('name1', 'url1'), ('name2', 'url2'))`
*   `GITHUB_URL`

Refer to [Pelican's documentation of settings](http://docs.getpelican.com/en/latest/settings.html) for description of these global variables.

### Theme-specific Global Variables

The theme also provides these global variables:

*   `GOOGLE_CUSTOM_SEARCH = 'your search engine unique ID'`

    The Fresh theme allows you to use [Google Custom Search Engine](http://www.google.com/cse/) as the search engine for your static website!

    Find the **search engine unique ID** of the search engine you set up in [Google Custom Search Engine's control panel](http://www.google.com/cse/manage/all).
    Assign this ID to the `GOOGLE_CUSTOM_SEARCH` variable, and a Google custom search bar will appear in the navigation bar.

*   `HIDE_CATEGORIES_FROM_MENU = True`

    If you want to hide categories from menu, you can do that by setting `HIDE_CATEGORIES_FROM_MENU` to `True`.


## License

Copyright (c) 2013, Jui-Shan Liang &lt;jenny@jsliang.com&gt;

All rights reserved.

Licensed under GPL v2.