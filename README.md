# <img src="https://www.svgrepo.com/show/452210/git.svg"  width="40" height="40"> Git


I'm eager to share a few Git commands that I utilized to build my GitHub portfolio
- [Creating, cloning, pushing and pulling repositories](#task-1)
- [Creating, adding remote repositories](#task-2)


## Task 1


##### Creating, cloning, pushing and pulling repositories  
```git
git init amzvdk                                       # Create your repository with the same name as your username 
git clone git@github.com:amzvdk/amzvdk.git      # Clone your repository on your computer to a separate folder
git clone git@github.com:testrusau/testrusau.git            # Clone github.com/testrusau/testrusau on your computer to a separate folder
cd testrusau                                                # Push data from testrusau repository to your own one 
git push git@github.com:amzvdk/testrusau.git main:main
git commit -m "commited change description"                 # Open the README.md file and replace each block with a separate commit 
git push 

```
## Task 2

##### Creating, adding remote repositories  
```git
git init sql                                                # Create separate repository for portfolio item 
git remote add sql https://github.com/amzvdk/sql.git  # Declarie repository remotely 
README.md edited manually                                   # Add links to your repositories to the README.md file
git commit -m "commited change description"                 # Push changes to remote repository
git push                                                     




```
