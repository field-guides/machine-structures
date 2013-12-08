# Machine Structures Field Guide

## What is This?
This repository temporarily exists in efforts to collaborate with staff and student in UC Berkeley's CS61C class and create a synopsis of Machine Structures. 

___
## How to Use?
If you would like to contribute here is how you can help:

 Raise in Issue if you notice any errors.

If you would like to add or modify content you will need to know the following.

The guide itself is written in [MultiMarkdown](http://fletcherpenney.net/multimarkdown/) syntax.
I used [Pandoc](johnmacfarlane.net/pandoc/) to convert the `machine-structures+markdown_mmd.md` into `machine-structures.pdf`. 

### Great So Here is How to Contribute: 

Please download Pacdoc [here](http://johnmacfarlane.net/pandoc/installing.html) and Latex [here.](http://miktex.org/).

Pandoc converts the Markdown into a PDF via Latex using this command:
`pandoc machine-structures+markdown_mmd.md --template=resources/guides.latex --toc --toc-depth=5 -s -o machine-structures.pdf` 

All specialized latex formating is done in the file called `guides.latex` in the `resources` directory. 

All images are in the `images` directory of the  `resources` directory. 

After you make any changes and test that it converts sucessfully into a PDF (**VERY IMPORTANT**), please fork the repository, make the modifications, and submit a pull request [(How To)](https://help.github.com/articles/using-pull-requests).

If everything looks good I will accept or else raise and issue. Thanks!

___
## How to Become an CoAuthor?
This basically means you get free push acess + your name in the colophon for future generations of Computer Scientists to marvel at.

### What You Need To Do

- Find more than 10 unique errors.

- Contribute more than 2 sections.

Please note if I find your work to be of quality I can add you as a collaborater  before the requirements are met. Likewise if you are submitting useless work or are trolling, you will never be a collaborater.  Thanks!

