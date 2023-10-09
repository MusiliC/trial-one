# DevOps Assignment 1
## Creating a repo from local machine and push to remote
### Steps: 
#### 1. Creating  Git Folder
     mkdir myproject  
     cd myproject   

#### 2. Initialize Git 
        git init 
        
#### 3. Adding New Files  
        You just created your first local Git repo. But it is empty.

        Type 'ls' which will list the files in the directory.

        Then we check the 'Git status' and see if it is a part of our repo:

 #### 4. Git Staging Environment  
         One of the core functions of Git is the concepts of the Staging Environment, and the Commit.

         git add . //Adds all files
         git add file.extension/folder -> staging a particular file or folder  

 #### 5. Git Commit
          Since we have finished our work, we are ready move from stage to commit for our repo.

          When we commit, we should always include a message.

          Eg. git commit -m "Updated index.html with a new line"  

  #### 5. Create a Repository on GitHub
          Assuming you have a github account. you create a new repo;

  #### 6. Push Local Repository to GitHub
          Since we have already set up a local Git repo, we are going to push that to GitHub:

          Copy the URL, or click the clipboard for the repo we had setup             

          To push the main repo, you first have to add the remote server to Git by running 'git remote add <repo url>'.

          Finally you push with the following command:

          git push -u origin <branch-name>