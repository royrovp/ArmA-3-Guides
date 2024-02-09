# Guidelines
This page should help you with understanding some basic principles of mkdocs and markdown.

## Markdown
Markdown is a markup language similar, in functionality, to HTML, but it's a bit easier to read and write.
While HTML tags are permitted in Markdown, I highly recommend using markdown syntax over html where possible.  
For example:  
    - use **double spaces** at the end of the line to create a new line, instead of using `<br>`
    - use **double asterix** for bold text instead of `<strong>`
Here is a cheatsheet of all things you can write using  Markdown check [this link](https://github.com/im-luka/markdown-cheatsheet)  

## Mkdocs
Mkdocs is a static site generator which takes our markdown files and plugins as declared in `mkdocs.yml` and generate a full webpage.  
When creating a new category you'll just need to create a new folder named like the category you want (e.g `Contributing`) and you'll add your .md files in that folder.
One thing to note is that the name of the page is always the first `# text` line. 
