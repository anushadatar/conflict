# Conflict (Metals)
Olin College SP20 Metals, Mining, and the Environment Final Project completed by [Abby Fry](https://github.com/amfry),  [Grace Montagnino](https://github.com/gracemontagnino), and [Anusha Datar](https://github.com/anushadatar). 

## Summary
For this final project, we conducted technical and contextual research on conflict metals and presented some of our findings on this [website](https://anushadatar.github.io/conflict/).

## Modifying the Website

The website's source code exists in the [docs/](https://github.com/anushadatar/conflict/tree/master/docs) directory. To modify any of the existing pages, edit the markdown file associated with the page, ad the new content will load on the webiste. 

To add a new page, add a new markdown file to the [docs/](https://github.com/anushadatar/conflict/tree/master/docs) directory. with the following header (populate TITLE_OF_PAGE with the actual title of the page). 
```
---
layout: "default"
title: TITLE_OF_PAGE
---
```
Then, add a link to your page in the navigation bar located in the [default layout page](https://github.com/anushadatar/conflict/blob/master/docs/_layouts/default.html) after the comment flagged for adding navbar items. Add the item with the following syntax, with MARKDOWN_FILENAME replaced with the filename of the markdown file (without the .MD extension) and TITLE_OF_PAGE replaced with the navigation bar item title.

```[html]
<! –– FLAG: Add navbar items here -->                                                   
<a href="{{site.baseurl}}/MARKDOWN_FILENAME.html"> TITLE_OF_PAGE</a> <br>

```
