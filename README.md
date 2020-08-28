[![Screenshot of the Website](https://raw.githubusercontent.com/mikepierce/conference-website-template/master/screenshot.png)](https://mikepierce.github.io/conference-website-template/)

---

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a-Coffee-orange)](https://www.buymeacoffee.com/mpierce)

An HTML/CSS website template perfect for a small academic conference. 
It's simple and easy to use, to contrast with something slicker but cumbersome like [hoverboard](https://github.com/gdg-x/hoverboard). 
You can [explore it live here](https://mikepierce.github.io/conference-website-template/).

## Installation

If you have access to a department web server for hosting, 
then using this template is as easy as cloning this repository 
directly into the `.www` folder in your home directory.
If not you can pretty easily host a website using this template using [github pages](https://pages.github.com/).
See that link for more details, but the basic procedure is this:

 1. Create a repository on GitHub titled `username.github.io`, 
 where *username* is your username on GitHub.

 2. Fork this repository, being sure to give your repository a more apt name,
 like *awesome-conference*.

 3. In your forked copy, go to *Settings* and scroll down to *GitHub Pages*.
 Under *Source* choose the master branch of your forked copy.
 Then your copy of the website will be hosted at `username.github.io/awesome-conference`.

## Beautiful Math with MathJax

It may be helpful to include mathematical notation on this website,
especially in the abstracts of talks. 
This can be done using [MathJax](https://github.com/mathjax/MathJax).
For an example see the [*programs* page](https://mikepierce.github.io/conference-website-template/program/) of the template site.
To include math in a page of this website, include the line

````HTML
<script type="text/javascript" async 
    src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=default"> 
</script>
````

in the `<head>` of that page. Then math can by typeset by using LaTeX's math notation enclosed in `\(...\)` delimiters.

## Sitemap

The `sitemap.xml` helps search engines understand the structure of the site.
In this file, each instance of "WEBSITE" should be replaced
with the actual address where this website is being hosted.
See the [sitemaps protocol page](https://www.sitemaps.org/protocol.html) for more details.
