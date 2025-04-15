# Ai-Startup-Website
This is my first repository as a devops engineer


## In this  mini project which is "HANDS ON GIT PROJECT", i will be showing how two people can co-operate on the same workspace without infringing the main and both work effectively on their branches

* ## Part 1: setup and intial configuration 
* we therefore install git and also create a github account
* once thats done we open a repository 
![](./Images/1.%20github%20dashboard.png)

* we are going to name our new repository "Ai-startup-website" we also initialize redeme file and we live the reopository open for all workers to view and drop some insight 
![](./Images/2.%20git%20repo.png)

* we are going to open a workspace folder on our computer, which is where we would be doing most of our work in and aslo clone our repository in our work space which will make our work efficient 
![](./Images/3.%20git%20clone.png)

* This is where we connected to the workspace and we used our clone "url"
![](./Images/4.git%20project.png)

* All that is done we need to create a branch for the two workers which i will call "tom and jerry"
we would use "cd ai-startup-website" to get to the directory and we are going to create a file in our visual studio code which we would call "index.html"
![](./Images/7.%20tom%20index.png)

* this how we must pull push and also commit the new branch 
![](./Images/10.git%20status.png)


## Part 2: This is where we simulate both tom and jerry work 
* To simulate both tom and jerry working on the same laptop, you will switch between two branches, making, changes as each other, we will also create a new branch for jerry
 
 * ## Tom's work: 
 we would navigate to the directory we just cloned using series of command "cd ai-startup-website"
 "git branch"
 "git checkout -b update-navigation"
 ![](./Images/11.%20git%20branch%20checkout.png)

* #### Recall we created an empty "index.html" in the main, the file will also exist in the "update-navigate-branch" and we will open the index file and input our correction or patch
![](./Images/7.%20ttom%20index%202.png)

* Then we use git status if the index has been indicated or pushed
![](./Images/14.%20git%20status%20updated.png)

* Then we stage toms changes so it wont interruptt the main work space and can be commited or tested or mergerd
by using "git add index.html" and "git status"
![](./Images/Screen%20Shot%202025-04-15%20at%202.59.46%20PM.png)

* then we commit tom changes with these commands shown bellow
![](./Images/16.%20update%20navigation.png)

* This sends tom commit from the local branch from the laptop to github repository, its like publishing your work for orther to see and interact with.

# Jerry work
* Switch to the main branch
* create a new branch for jerry
* make changes and then
* stage , commit and also push these changes to github

* Git checkout main
![](./Images/17.git%20checkout%20main.png)

* Git pull origin update-navigation
![](./Images/17.git%20checkout%20main.png)

* Then we creat a new branch for jerry workspace 
which we use " git checkout -b add-contact-info"
 ![](./Images/19.png)

 * Now that the branch has been created we need to open a file for jerry so he can have he's input 
 ![](./Images/5%20jerry%20input.png)

 * ## Now that all the codes has been computed the last and final step for jerry to do is to stage, commit and push these changes to github

 ![](./Images/19.png)
 