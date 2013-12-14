# Machine Structures Field Guide

## What is This?
This repository temporarily exists in efforts to collaborate with staff and student in UC Berkeley's CS61C class and create a synopsis of Machine Structures for everyone's benefit. 

___
### Installing and Forking
**Please install Latex if you have not already**

To use the template and make the work easy, we use [Pandoc](http://johnmacfarlane.net/pandoc/). 

**Download Links**
- [Windows](https://pandoc.googlecode.com/files/pandoc-1.12.2.1.msi)
- [Mac](https://pandoc.googlecode.com/files/pandoc-1.12.2.1.pkg.zip)

Please fork the repository, make your additions, edit, subtractions, and submit a pull request [(How To?)](https://help.github.com/articles/using-pull-requests).

___
### Writing

All the organization in done in a extensible syntax called Markdown which is extremely simple to learn (as in < 10 minutes) and is a joy to use.

[5 Minute Tutorial](http://daringfireball.net/projects/markdown/basics)

You can mix and match Latex and and Markdown to create the guide. 

Latex is great for writing the equations and mathematical text.
Markdown is great for English and most importantly for simple organization. 

Pandoc creates a table of contents using the hashtag structures to represent the levels. It is really a painless and fun process.

You can embed images and links and all that fantastic stuff!
[5 Minute Tutorial for Markdown](http://daringfireball.net/projects/markdown/basics)

Feel free to contact me (Krishna) [here](mailto: kcparashar+cs61c@gmail.com)

___
### Compiling
Run this command in your terminal where the directory is to compile the guide:

``pandoc machine-structures+markdown_mmd.md --template=resources/guides.latex --toc --toc-depth=5 -s -o machine-structures.pdf``

All specialized latex formatting is done in the file called `guides.latex` in the `resources` directory. **You shouldn’t need to change this.**

All images are in the `images` directory of the  `resources` directory. 

___
### Opening

Pandoc will use the above command to generate a PDF called:
``machine-structures.pdf``

You can open them in your favorite PDF reader and marvel at the sheer beauty!

Thanks and enjoy!

___
## Incentives
If you Contribute Two or More Sections to the guide, your name will be added to the the colophon for future generations of Computer Scientists to marvel at!

Perhaps the biggest incentive of all is that by trying to find a good way to teach others the material, you will probably learn so much more than you would by simply reading it yourself. Plus the other person benefits. It’s really a win-win!
