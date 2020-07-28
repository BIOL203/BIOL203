[Course Website](https://biol203.github.io/BIOL203/)


## Important Files:
* index.md : Content for homepage
* \_config.yml: basic settings, theme, site title, how to structure links to posts, etc.
* \_include and \_layout files: HTML code for the theme layout. Defaults for this theme (minima) are [here](https://github.com/jekyll/minima), but if HTML-savy, you can copy and paste any file into these folders and edit locally to override the default layout.

## Adding Pages:
* Add file and name it pagename.md
* Add a [yaml](https://jekyllrb.com/docs/front-matter/) header to the file, with layout: page
* Commit changes
* In \_config.yml, add pagename.md to header_pages option to add a link in main site header
* If you don't want the page in the main header (such as for individual labs) the page can also be accessed at https://biol203.github.io/BIOL203/pagename.html through links

## Adding ToCs:
* In the .md documnet, add 
```
1. TOC
{:toc}
```
* For every header you don't want in the TOC, add directly below the header:
```
{:.no_toc}
```

## Formatting Pages (.md documents)
Formatted according to markdown. References on inserting lists, tables, images, links, headers, stylized text, etc:
 * https://www.markdownguide.org/cheat-sheet/#overview
 * https://about.gitlab.com/handbook/markdown-guide/
 
