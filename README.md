# mirageOS
is an open extendable cloud platform - often used as a CMS, or an E-Commerce Site, or for an online Publication, etc, sometimes used as a `wp-Eject` button...

# What is Mirage
Think about Mirage like a CMS in the cloud that comes with an Add-On store - like apps for your phone. It lets's developers create Bolts that can be installed to your site.

## Project Goals
Let's create a world where writers and creators (marketers, etc) benefit from the advancement of new technology allowing simple online publishing, to be augmented with the power of modern cloud platforms. Creators should not need to fire up their terminal, understand that YAML is not a an animal, or be a markdown expert. They, and their team, can write from anywhere, and host their own content in a format that is incredibly fast and enjoyable for readers.

### Goals
- Support multiple authors (not developers) writing from varried places
- Allow for simple site and theme extensiblity via `Bolts`
- Web-based editing of the Theme & config
- Web-based editing the site config
- Web-based purchase/install of bolts 
- Web-based purchase/install of Themes 
- With Mirage it is a challenge to create a slow web-page.
  - Themes should be syntax validated and performance graded before being made available
  - Themes should strive towards being a Progressive Web App
  - BoltOns shold not slow down the Reader's Happy Path for the site.
- Keep an attack vector minimized via the architecture not via `10x Infosec Developers` making every plugin (or in this case BoltOn) 
- Encapsulated in a Software definition
- Multi-cloud deployable

## Inspiration:

Mirage draws inspiration from the proliferation of static site generators, notably from:
- [Hugo](http://gohugo.io/)
- [Hexo](https://hexo.io/)
- [Gatsbyjs](https://www.gatsbyjs.org/) 
- [Jekyll](https://jekyllrb.com/)

Mirage also draws inspiration from other players helping developers delploy these sites like:
- [Netlify](https://www.netlify.com/)
- [ZEIT](https://zeit.co/)
- [CosmicJS](https://cosmicjs.com/)
- [Contentful](https://www.contentful.com/)

All of the products represented by the sites above, are in some part, attempting to create the same world that Mirage wishes for everyone. A seemless transition of human thoguht to written page - without the mental baggage of worrying about what could go wrong.

## BoltOns vs Plugins
Plugins are not the enemy. Plugins represent some of the truest software ideals, of writing code that does something useful, and then sharing it with friends and the public. Plugins just represent an outdated way of dealing with security, performance, and code conventions.

`BoltOns` are an attempt to fix this via a more rigorus architecture that creates sandboxed, "approved" mechanics to do the same thing. Most important is the difference in execution model.

The Mirage Project is a work in progress, and can use your help if you think life gets a little better when we can write more, and manage plugins less.

