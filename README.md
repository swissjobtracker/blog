# Blog of the Swiss Job Tracker Project

see swissjobtracker.github.io

## Update Blog

Read the quarto readme

The blog uses [quarto](https://quarto.org/docs/websites/website-blog.html) to generate HTML content from markdown blog post input. 
To update the blog: 

1. clone this repository to your local computer (once)
- use the github username (not gitlab)

2. make sure quarto cli is installed (once)

- for every new post, generate a new folder in the posts/announcement folder and generate there a new qmd file 
- if the qmd file is rendered we see a preview of the webpage but only if the scripts runs on a locally installed RStudio

3. make edits 
4. add & commit edited to files including illustrations & images to git version control 
5. run `quarto publish gh-pages .` 

> note you have to enter the password of your RSA Key pair multiple times if you use such a password.




