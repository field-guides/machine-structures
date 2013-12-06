# Machine Structures Field Guide

## What is This?
This repository temporarily exists in efforts to collaborate with staff and student in UC Berkeley's CS61C class and create a synopsis of Machine Structures. 

## How to Use?
If you would like to contribute here is how you can help:
1. Raise in Issue if you notice any errors.
2. If you would like to add content you will need to know the following.

The guide itself is written in [MultiMarkdown](http://fletcherpenney.net/multimarkdown/) syntax.
I used [Pandoc](johnmacfarlane.net/pandoc/) to convert the `machine-structures+markdown_mmd.md` into `machine-structures.pdf`. 

Pandoc does this via the command: 
`pandoc machine-structures+markdown_mmd.md --template=resources/guides.latex --toc --toc-depth=5 -s -o machine-structures.pdf` 

All specialized latex formating is done in the file called `guides.latex` in the `resources` directory. 

All images are in the `images` directory of the  `resources` directory. 

After you make any changes and test that it converts sucessfully into a PDF (**VERY IMPORTANT**), please raise and issue with the attached `.md` file list. 

# How to Become an Author?
- Find more that 10 unique errors.
- Contribute more than 2 sections.

