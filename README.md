Hexo theme: Apollo
=================

**This hexo theme is modified from SANOGRAPHIX.NET**

**And is further adjusted for better Chinese illustration**

[Original](https://github.com/sanographix/tumblr/tree/master/apollo) (Tumblr theme)  
[Demo](http://howyoung.info/)


##Installation

###Install

Run this command from inside your hexo project
``` bash
$ git clone https://github.com/YANG-H/hexo-theme-apollo.git themes/apollo
```

**Apollo requires Hexo 2.4 and above.**

###Update

``` bash
cd themes/apollo
git pull
```

##Configuration

``` yml
# Header
menu:
    Home: /
    Archives: /archives
rss: /atom.xml

# Contact
contact:
    facebook: yang.hao.12 # Set your facebook id here
    twitter: aognay # Set your twitter id here

# Content
excerpt_link: Read More
fancybox: true

# Miscellaneous
google_analytics:
favicon: /favicon.png
```

- **menu** - Navigation menu
- **rss** - RSS link
- **contact** - Facebook & Twitter
- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **fancybox** - Enable [Fancybox](http://fancyapps.com/fancybox/)
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path
