# mirage
an open extendable cloud platform - used as a CMS, an E-Commerce Site, an Online Publication, a Wordpress replacement, etc

# What is Mirage
The easiest way to think about Mirage is "The static-site generator in the cloud." Mirage does not aim to be yet another static site generator from developers, but instead a static site generator for Wordpress, Squarespace, Blogger, and users. 

## THE Goal
The Goal of mirage is that marketers and other writers can benefit from the advancement of new technology allowing simplistic online publishing, but where the writter does not have to fire up the terminal, understand that YAML is not a an animal, or be an expert in markdown. Write from anywhere.

- Support multiple authors (not developers) writing from varried places
- Edit the Site's config from the Browser
- Edit the Theme & its config
- Allow for simple site and theme extensiblity via `BoltOns`
- Install Themes via the browser
- Install BoltOns via the browser
- Should make it hard to create a slow web-page
  - Themes should be syntax validated and performance graded before being made available
  - Themes should strive towards being a Progressive Web App
  - BoltOns shold not slow down the Reader's Happy Path for the site.

## Inspiration:

Mirage draws inspiration from the proliferation of static site generators, notably from:
- [Hugo](http://gohugo.io/)
- [Hexo](https://hexo.io/)
- [Gatsbyjs](https://www.gatsbyjs.org/) 
- [Jekyll](https://jekyllrb.com/)

Mirage also draws inspiration from other players helping developers delploy these sites like:
- [Netlify](https://www.netlify.com/)
- [ZEIT](https://zeit.co/)

All of the products represented by the sites above, are in some part, attempting to create the same world that Mirage wishes for everyone. A seemless transition of human thoguht to written page - without the mental baggage of worrying about what could go wrong.

## BoltOns vs Plugins
Plugins are not the enemy. Plugins represent some of the truest software ideals, of writing code that does something useful, and then sharing it with friends and the public. Plugins just represent an outdated way of dealing with security, performance, and code conventions.

`BoltOns` are an attempt to fix this via a more rigorus architecture that creates sandboxed, "approved" mechanics to do the same thing. Most important is the difference in execution model.

The Mirage Project is a work in progress, and can use your help if you think life gets a little better when we can write more, and manage plugins less.

