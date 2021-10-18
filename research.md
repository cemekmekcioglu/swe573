# Research

## Git

* Git is a version management system and different from Github. Github relies on Git.
* Git works on terminal.
* Git enables users to track changes made in the software. It visualizes who made what changes.
* There are repositories in git. These repositories are containers created specific to a software product/project.
* To create a repository, the command line is: 
  * git init
* To check the status of the repository, the command line is:
  * git status
* To add a file to the repository, the command line is:
  * touch file.js
* Once a change has been made, you may want to commit the change. This is a two step process:
  * First, you need to add the files/changes you would like to commit to the staging area.
  * Then, from staging area you commit to the selected branch.
* To add the files/changes to the staging area, the command line is:
  * git add file.js
* To commit the changes added to staging area, the command line is:
  * git commit -m "message"
    * where message is a string and is used to describe the nature of the commit
* Git allows users to see the history of the commits made in the repository, this history is called log. The command line is:
  * git log
* Once you added the file in the repository but you haven't committed yet, then if you check out the status (git status), you would see the files as "untracked files". On the other hand, if you have committed the files, but you have made some changes on them, then "modified file.js" would appear on the result screen for "git status".
* If you would like to add all of the changes to the staging area, you can do so without specifying a certain file name, The corresponding command line is:
  * git add.
* git log command presents users a history of commits. We can think of it as a time line, and git allows users to travel on that time line, meaning, one can retrieve the code which existed x commits before. To do so, the command line is:
  * git checkout <commit-hash>
    * where commit hash is given in the response of git log. It is an id unique to each commit.
* Another important feature git provides is branches. A repository has always a main branch, which can be considered as the main time line (concept of time line explained above). In this context, all the other branches created by the users are side time lines where changes are made and the main branch remains unchanged.
* When to use branches? For example you have an idea that requires a lot of changes in the project, and you don't know yet if these changes will be implemented or not. First, you would like to see what you project would look like after you made those certain changes. In this situation, you create a new branch and do all the necessary changes to see the outcome of your new idea where your main branch (project) stays the same.
* To see the branches in a repository, the command line is:
  * git branch
  * git branch command returns a list. In the list there is a branch namne with a "*". This star indicates which branch you are on at the moment. 
* To create a new branch, the command line is:
  * git branch <new-branch-name>
* If you would like to adapt the changes in a branch, then you want to have these changes in your master branch. For this purpose you need to merge the corresponding branch to the master branch. The command line is:
  * git merge <branch-name>
  
## Wikidata
  
* The most emerging feature of the wikidata is that it is an open base where all the knowledge is stored and shared. Humans and even machines are welcome to contribute. 
* Wikidata has sister projects as Wikipedia, Wikivoyage, Wiktionary, Wikisource, and others.
* Technically, wikidata uses structured data.
* Wikidata shares information via SPARQL and API's. 
* As for the API's, we can use both get and post methods to retrieve data. 
* In the get method you send the query (which is used to retrieve data according to your search) in the url
<img width="1060" alt="Screen Shot 2021-10-18 at 9 46 03 AM" src="https://user-images.githubusercontent.com/62806402/137681801-bcde75a1-fc79-4d3e-8bf3-75507744979d.png">
* In the post method you send the query in the request body
<img width="1057" alt="image" src="https://user-images.githubusercontent.com/62806402/137682051-47722198-d509-4abc-b23d-5d52b51d4d9a.png">
* Both api calls provide you with the data stored in wikidata and you can access them for free. 
* Other than api's, as mentioned above SPARQL may be used to access data.


