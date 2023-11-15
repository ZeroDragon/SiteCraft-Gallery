meta:
  title: Mate Theme
  date: 202306161417
  author: Zero
  excerpt: Original theme with examples for all posibilities supported
  image: content/images/mate.jpeg
  tags:
    - complete
    - template

## Mate Theme

![Mate](!{siteUrl}/content/images/mate.jpeg)

### What it Mate?

Mate is an argentinian herb that is used as tea (it is actually a tea leaf) and the name of this theme is because when I was developing this theme I was drinking a lot of Mate.

This is the base theme, nothing super fancy, and in fact it is the theme that you are looking right now.

> It features a liquid responsive design

This theme is also a showcase with all the options that can be used in the metadata of a blogpost, how to customize the bloglist and how to do imports in the `styl` files to reduce file size while developing a template.

Remember to use the contents of the theme you are wanting to use directly into the `/template` directory.

### File structure of this theme
```
─ template
  ├─ favicon
  │  └─ All favicon related items
  ├─ images
  │  └─ header.jpg
  ├─ partials
  │  ├─ blogList.pug # showcase of the list of post of the homepage
  │  ├─ blogList.styl # sepparated styl file so wont blotter the original style sheet
  │  ├─ foter.pug
  │  ├─ header.pug
  │  └─ headMeta.pug # where all the social media magic happens
  ├─ page.pug # this is used to render all single pages
  ├─ post.pug # similar to page, but this is used to render individual blog posts
  └─ styles.styl # primary stylesheet. Check those imports
```

### How to install
Just download the `mate.zip` file from [this repository](https://github.com/zerodragon/SiteCraft-Gallery) under `releases` and unzip it inside your `/template` directory (just the files not the directory)
