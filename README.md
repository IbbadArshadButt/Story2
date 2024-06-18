 --------TWO METHODS OF MERGE---------

                 ''''''''' From local GIT /From Terminal '''''''''

1- Go to story folder containing files namely chapter1,chapter2,chapter3. (Can check it by git log)
2- Create a new branch namely "alien-plot" from master/main branch.
3- For this purpose use command "git branch alien-plot".
4- Use "git branch" to check on which branch we currently are. 
5- Use "git checkout alien-plot" to switch to this new branch.
6- Make any change (addition/modification) to existing files in story folder/directory.
7- Now save all changes by using "git add .".
8- Also commit by using "git commit -m 'message'   ".
9- Now "git log" to check all changes and files in the directory.
10- Use "git branch to check on which branch we currently are.
11- Use "git checkout master" to switch to this main branch and create a file namely "chapter4.txt",add it and then commit, also log to check position.
12- Use "git branch to check on which branch we currently are and Use "git checkout alien-plot" to switch to this new branch.
13- We will see if our new changes are good enough to be merged to main. If yes the we go for merge.
14- Again use "git checkout master" to switch to this main branch.
15- Merge by using command "git merge alien-plot". Log to check all changes.
16- Now push to remote by using command "git push origin master -u".
17- We can see all steps in GitHub by going to Insights -> Networks -> Graphs.

                  
               ''''''''' From GitHub online/Remote interface '''''''''
1- Create new repository namely "Story2".
2- While creating repository, check the readme checkbox to create a readme file also in the repo. It is a txt file that contains info about our repository.
3- Create new file in the Story2 repo. Name the file as "chapter1.txt". Enter some text in the file. Commit the file changes, also enter commit message.
4- Go to branch dropdown, enter experimental new branch there.
5- Inside experimental branch, again go to chapter1.txt and make changes. Commit the file changes, also enter commit message.
6- Go to branch dropdown, go to the main branch. Create new file in the named as "chapter2.txt". Enter some text in the file. Commit the file changes, also enter commit message.
7- Go to "New pull request" a window showing comparison will be displayed.
8- Select "base as main" and "compare as experimental".
9- Enter the message as per change made. Click "create pull request".
10- A confirmation button "confirm merge" will show up.
11- Now if we want to compare steps with local method steps.
12- We can see all steps in GitHub by going to Insights -> Networks -> Graphs.
