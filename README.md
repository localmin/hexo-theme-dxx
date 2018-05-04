# hexo-theme-abc

基于[hugo-theme-cactus-plus](https://github.com/nodejh/hugo-theme-cactus-plus)修改

## Installation

plugin dependencies:

- hexo-renderer-pug
- hexo-generator-feed

clone theme

    git clone https://github.com/shinux/hexo-theme-adoubi.git themes/abc

modify site config

    theme: adoubi

replace `themes/adoubi/sources/images/favicon.ico` with your own preference

upgrade

    cd themes/abc
    git pull origin master


## Display images in article:

if image located at site's `source/images` :

    <img src="/images/your-image.png">

> images will be limited to `max-width: 100%` compared to parent class `post-content`.

**NOTICE: hexo will use site's source preferentially**

## Upgrade Logs

v0.0.2 May 12 2017:

- remove big-black-dirty-ugly header and personal logo.
- make feed icon more hidden.
- hide post date on list page.

## Copyright

resources usage:

- Myriad font
- normalize.css

Keep `Theme By Adoubi , Powered By Hexo.` in footer and do whatever you want.
