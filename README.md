# Nimiq Documentation Theme

## Motivation
For the [Nimiq Blockchain](https://nimiq.com) we wanted to design a documentation theme which has the following properties:

- is a Jekyll theme for GitHub Pages; one-click installation
- works with multiple `.md` files
- automatically generates table of contents from filenames and headings
- clean design focused on the content and its typography
- mobile layout
- works without javascript

## Installation

In your project's root folder create a `_config.yml` like this:
```
remote_theme: nimiq/doc-theme
title: "Nimiq"
description: "Developer Reference"
```

Your `readme.md` will become your `index.html`.

## Format 

- Every page must have exactly one `#top-heading` because it is used in the navigation as label for the item. All other headings should be at least second-level headings like `##second-level`.


## Real World Examples 

- [Nimiq Developer Reference](https://nimiq.com/developer-reference)
