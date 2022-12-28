 # 1. What is remote git repository?
A remote git repository is nothing but a space in a remote computer which allow us to manage our project. A benefit of having a remote git repo are followings:

multiple developers can work remotely on same repo
you can push your local file changes to server
Think about this way if you only have a local git repo and what if something went wrong with your computer? What if you want other developers to work on the same project?



# 2. Sign up for Github

 How to create a github repository?
Log on to your github account. Click on + icon located on top right corner to create a new remote git repo as shown in image below:


Click on New Repository menu item. You will now see a screen shown below where you need to put repostory name, description (optional), select public or private and hit Create Repository button:


Next, it will create a new blank repo and will take you to the following screen. It will gives you following two options:

# 3. Creating a new repo

In our previous tutorial, we created a local git repostitory. We want to add that local git repo to our newly created git remote repo.

Let's make our local git repo to be aware of our newly created remote git repo. So that you can push your local git changes to remote git repo.

# 4.  How to fetch remote changes using git?
Now, that we have a remote git repo and we know that it is empty. We have our local git repo with some files. Our task is to move our local git changes to remote git repo.

When we created a new remote git repo by default it creates a master branch. We are at beginners level so at this moment dont worry about branches and what are they we will learn them as we move on.

For now, just think that you have only one branch called master where you need to push your local git changes. We need to use fetch command to get all new changes from remote git repo.

Let's run following command to get all the data from remote git:

fetch remote changes/refs
git fetch

you can also use following 
command instead of git fetch
git pull​
 What is the difference between git pull and git fetch?
Git fetch will only fetch all the remote changes to local git repo.

Git pull will first fetch all the remote changes to local git repo and performs merge operation which means if you and other developer work on the same file and both made some changes. They will be merged together with git pull.


git push -u origin master​
You will see following output with above command:


We have successfully pushed our local git changes to remote git repo.