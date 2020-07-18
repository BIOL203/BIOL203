[Website](https://biol203.github.io/BIOL203/)


## Files
* index.md : Content for homepage
* \_config.yml: basic settings, theme, site title, how to structure links to posts, etc.

## Adding Pages:
* Add file and name it pagename.md
* Add a [yaml](https://jekyllrb.com/docs/front-matter/) header to the file
* In \_config.yml, add page to header_pages option to add link in site header
* If not added in \_config.yml, the page can also be accessed at https://biol203.github.io/BIOL203/pagename.html

### Adding TOCs:
* At top of the documnet, add 
```
1. TOC
{:toc}
```
* For every header you don't want in the TOC, add directly below the header:
```
{:.no_toc}
```


## Pages are formated in markdown:
 * https://about.gitlab.com/handbook/markdown-guide/
 * https://rstudio.com/wp-content/uploads/2015/02/rarkdown-cheatsheet.pdf
