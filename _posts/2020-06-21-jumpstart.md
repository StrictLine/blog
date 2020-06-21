---
title: Jumpstart of the blog
type: thought
---

## Go with CMS?
The common approach to start a blog is installing or renting a Wordpress site, for more advanced requirements carefully choosing the right CMS solution (e.g. Joomla, Drupal, Typo3) and evaluate its features and maintenance demand. The whole process of building it up is very time consuming and bad decisions lead to a slow unattractive website, which need to be optimized by caching or such.

In order to get ready to publish as quickly as possible you might consider to build static HTML pages, if you have some web development skills. Compared to the common approach above it's more time efficient and you invest your time mostly into the **content** or the **appearance**. Both of them are visible and matter for the user, and nobody cares what you did under the hood.
But at the first glance static HTML pages are redundant, you need to copy the same header, navigation bar, etc. to all your pages, and if you want to change these parts, the change has to be done in each page. Here comes Jekyll into the play...

## Jekyll & GitHub Pages
The technology behind [GitHub Pages](https://pages.github.com/) provides a way for static site generation with the so-called Liquid templating language. After building the site you only need a webserver which can server HTML pages or push it to GitHub and set up this feature.

It's recommended to start with a free template to get a feeling how it works, and the creator of the template might have integrated some useful features pre-configured, so this don't need to be implemented on your own.