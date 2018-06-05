---
title: "Contributing to हिन्दु-विचाराः Hindu thoughts"
---

This is a [Hindu(tva) site](http://hindutva.github.io/). All data and content here are available under the Creative Commons Attribution 4.0 International License.

You can help maintain this resource!
- You're welcome to contribute. All contributions will be reviewed and merged if accepted.
- You're welcome to mirror our writing on your server or even fork off! More copies and backups are better.

# Caution
- Please protect your identity from violent haters - use pseudonymous git accounts if needed. (Git configuration tips: [SO](https://stackoverflow.com/a/45327500/444644).)

# Technical intro
- This site is produced using the Jekyll static website generator.
- We use a customized version of the [tomjoht/documentation-theme-jekyll](http://github.com/tomjoht/documentation-theme-jekyll) theme.
- We use disqus for comments.
- We use google analytics for getting stats.

# Guidelines
- Navigation bars configuration: In _data, topnav.yml and sidebars/*.yml.
- Pages are located under pages/
  - Regarding the per-page YAML front-matter :
      - Though the pages are hierarchically arranged in subfolders, the final pages are flatly placed - so make sure your permalinks don't contain '/'.
- Local tests:
  - Run `bundle exec jekyll serve`
  - Look at https://localhost:4000/
  
