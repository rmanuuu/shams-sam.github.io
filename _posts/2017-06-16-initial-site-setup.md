---
layout: post
title: The One With Github Pages
categories: []
tags: [04. setup]
description:
comments: true
---

[GitHub Pages](https://pages.github.com/){:target="_blank"} is a web hosting service offered by [GitHub](https://github.com/){:target="_blank"} for hosting static web pages for GitHub users, user blogs, project documentation, or even whole books.
It is integrated with the [Jekyll](https://jekyllrb.com/){:target="_blank"} software for static web site and blog generation. The Jekyll source pages for a web site can be stored on GitHub as a Git repository, and when the repository is updated the GitHub Pages servers will automatically regenerate the site.
GitHub Pages was launched in late 2008. As with the rest of GitHub, it includes both free and paid tiers of service, instead of being supported by web advertising. Web sites generated through this service are hosted either as subdomains of the github.io domain, or as custom domains bought through a third-party domain name registrar.

Steps for setup:
* Fork this repository.
* Update repository name to `<user_name>.github.io`.
* Customize `_config.yml` to match user credentials.
* In `_includes/comments.html` edit `disqus_shortname`.
* Update `index.html` bio.
* Commit the changes.
* Done!

This site is build on top of the customizations by [psteadman](https://github.com/psteadman){:target="_blank"} on [lanyon](https://github.com/poole/lanyon){:target="_blank"} theme which derives from [poole](https://github.com/poole){:target="_blank"}.
Head over to the post [Using Jekyll, Poole and Lanyon to setup my github user page](http://patricksteadman.ca/2014/08/04/lanyonsetup/){:target="_blank"} for further references.

Additions:
* Adding [MathJax](http://docs.mathjax.org/){:target="_blank"} for adding equations.

## REFERENCES:

<small>[Github Pages - Wikipedia](https://en.wikipedia.org/wiki/GitHub_Pages){:target="_blank"}</small>

<small>[Using Jekyll, Poole and Lanyon to setup my github user page](http://patricksteadman.ca/2014/08/04/lanyonsetup/){:target="_blank"}</small>
