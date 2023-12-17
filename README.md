[![Screenshot of the Website](https://raw.githubusercontent.com/mikepierce/conference-website-template/master/screenshot.png)](https://mikepierce.github.io/conference-website-template/)

An HTML/CSS website template perfect for a small academic or technology conference or seminar.
The template is quick to deploy and straightforward to customize.
You can [explore it live here](https://mikepierce.github.io/conference-website-template/),
and see some folks' use of the template
[here](https://math.ucr.edu/~mathconn/) 
and [here](https://data-science-conference.github.io) 
and [here](https://aquaticdatasciopensci.github.io) 
and [here](https://comp-expe.github.io) 
and [here](https://enba-phd-call.github.io)
and [here](https://strl2022.github.io).
I'd be happy to see the site you create from my template ☺

## Installation

If you have access to a server for web hosting, 
perhaps through your company/university or department, 
then using this template is as easy as cloning this repository 
directly into your public HTML directory.
If not you can pretty easily host a website using this template with [GitHub Pages](https://pages.github.com/).
See that link for more details, but the basic procedure is this:

 1. Create a GitHub repository named `username.github.io`, 
 where *username* is your username on GitHub.

 2. Click the *Use this template* button above, 
 being sure to give your copy of this repository a more apt name,
 like *awesome-conference*.

 3. In your copy go to *Settings* and scroll down to *GitHub Pages*.
 Under *Source* choose the master branch of your forked copy.
 Then your copy of the website will be hosted at `username.github.io/awesome-conference`.

## Editing the Template

If you have not edited HTML/CSS to design a webpage before, 
I encourage you to read 
[How to Build a Personal Webpage from Scratch](https://rutar.org/writing/how-to-build-a-personal-webpage-from-scratch/)
by Alex Rutar, particularly the 
[Crash course in HTML and CSS](https://rutar.org/writing/how-to-build-a-personal-webpage-from-scratch/#crash-course-in-html-and-css) 
section.

## Beautiful Math with MathJax (optional)

It may be helpful to include mathematical notation on this website, especially in the abstracts of talks. 
This can be done using [MathJax](https://github.com/mathjax/MathJax).
For an example see the [*programs* page](https://mikepierce.github.io/conference-website-template/program/) of the template site.
To include math in a page of this website, include the lines

````HTML
<script type="text/javascript" async 
    src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=default"> 
</script>
````

in the `<head>` of the HTML file. Then math can by typeset by using LaTeX's math notation enclosed in `\(...\)` delimiters.

## Sitemap (optional)

The file `sitemap.xml` helps search engines understand the structure of your site.
In this file, each instance of "WEBSITE" should be replaced
with the actual address where this website is being hosted.
See the [sitemaps protocol page](https://www.sitemaps.org/protocol.html) for more details.

## Alternatives

The simplicity of the HTML/CSS source for this template is its strongest feature.
For something more slick or modern or sophisticated or complicated:

 - [Hoverboard](https://github.com/gdg-x/hoverboard) is beautiful but requires some tech know-how to setup. 

 - You can build something from scratch based on a 
 [GitHub Pages site with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll) 
 or a template from [Pixelarity](https://pixelarity.com).

