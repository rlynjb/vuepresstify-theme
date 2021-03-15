# vuepressify-theme

this is a Vuepress theme based off of Vuetify

## Post Category and File Structure
when you create a folder under `site/docs/codebits`, its considered a category

when you create nested folders, its still considered a category




## How Post work

format of post file name.
`YYYY-MM-DD-title.md`

if date is present, post will be published

```
---
title: ''
layout: Post
date: date will be display on Post or thumbs
img: <usually cover of a gallery>
imgs:
  - 'path/to/img/here': 'caption'
  - 'path/to/img/here': 'caption'
---
```

### Post frontmatter options

layout - available layouts can be found in `docs > .vuepress > theme > layout`

date - date that will be displayed on post and thumbnails
