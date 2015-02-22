---
title: "helloworld"
author: "Miguel R Ramirez"
date: "Sunday, February 22, 2015"
output: html_document
---

## This is a Mardown file


### Extra Information (Not Required by Final Project)

I want to include the steps a I followed to acomplish this part of the final project. This was the most difficult task for me in this course. It's very simple but took me a while to find the way

1. Using RStudio create the file helloworld.md  
2. Create a working directory to recieve the remote repo: mkdir *finalproyect*
3. Change workpath to the created *finalproyect* directory cd *finalproyect* 
4. Initialize *finalproyect* directory as a local Git repository: git init
5. Point this local repository to the GitHub corresponding remote *datasciencecoursera* repo, using *origin* as nickname for the remote path: git remote add origin https://github.com/mramirezv/datasciencecoursera.git
6. Clone the remote repo *datasciencecoursera* in the local directory *finalproyect*: git clone https://github.com/mramirezv/datasciencecoursera.git
7. Save this file in the local datasciencecoursera repo
8. Update Git (a new file was added to the local repo *datasciencecoursera*): git add -A
9. Because new lines were added to this file, changes had to be committed: git commit -m "including last lines in helloword.md"
10. Upload the locally modified *helloworld* file to the remote *datasciencecoursera* repo: git push 
