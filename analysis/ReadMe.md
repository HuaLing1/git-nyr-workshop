Workshop Materials (change in local + another edit made on github)
- git checkout <hash> <filename>: gets to the specific version of the file
- git checkout master: comes back from detached head or a separate branch to master 
- git log --graph --oneline: visualizes brances

## Adding new things after 4:45pm. 

Branch workflow
- git branch new_branch
- modify & commit
- git checkout master
- git branch -a
- git merge new_branch master: this merges the new_branch into master

When there are edits that happen on different line across different locations, we can easily merge them
However, when there are changes in the same line across remote and local. There will be conflict. 
It's a best practice to enter new line with a new sentence.
In Markdown, two spaces lead to a new paragraph.


