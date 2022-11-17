# Blog of the Swiss Job Tracker Project

see swissjobtracker.github.io

## Update Blog

Read the quarto readme

The blog uses [quarto](https://quarto.org/docs/websites/website-blog.html) to generate HTML content from markdown blog post input. 
To update the blog: 

1. clone this repository to your local computer (once)
	- use the ssh link starting with git@github...

2. make sure quarto cli is installed (once)

3. for every new post, create a new folder in the posts/announcement folder and create a new qmd file 
	- put figures you want to use in the same folder
	- Define the necessary commands between --- for the header. Write the blog text below
	- if the qmd file is rendered we see a preview of the webpage but only if we have the newest version of RStudio

4. add & commit edited to files including illustrations & images to git version control 
5. run `quarto publish gh-pages .` 

> note you have to enter the password of your RSA Key pair multiple times if you use such a password.




