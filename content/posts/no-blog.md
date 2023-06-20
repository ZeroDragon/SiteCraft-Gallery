meta:
  title: Simple Theme
  date: 202306191824
  author: Zero
  excerpt: This is a simple site without blog, just a landing
  image: content/images/no-blog.png

## Simple Theme

![Mate](!{siteUrl}/content/images/no-blog.png)

<br/>

This is as simple as it gets, no blog, no entries, just a header, footer and simple landing page. This build does not include favicons, you can add yours. 
No pages defined in `site.yml`. But you can add as desired to `content/*` and define them so they can be displayed at the header

### File structure of this theme
```
─ template
  ├─ favicon
  │  └─ All favicon related items
  ├─ images
  │  └─ header.jpg
  ├─ partials
  │  ├─ foter.pug
  │  ├─ header.pug
  │  └─ headMeta.pug # where all the social media magic happens
  ├─ page.pug # this is used to render all single pages
  └─ styles.styl # primary stylesheet. Check those imports
```
<br/>

### How to install
Just download the `template.zip` file from [this repository](https://github.com/ZeroDragon/SiteCraft-simple-theme) under `releases` and unzip it inside your `/template` directory (just the files not the directory)
