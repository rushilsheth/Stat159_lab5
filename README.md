User A: Rushil Sheth 
User B: Lily Li  

---  

First, we created a repository on one user's Github account. Then we added a collaborator and proceeded to make changes. We then pushed and pulled (updating on both ends) our changes onto Github using the command line. 

---  

There was a conflict when both users were trying to push without pulling first because there were changes on both ends. To resolve the conflict, you must first commit your local changes, pull, then push.  
  
---  

When a new branch was created and unmerged, we allowed for some experimental changes. Later, when User B was satisfied, the task3B branch was merged with the the master.  

---  

For each user A(B):
git checkout -b "Task5B"
(make changes)
git add .
git commit -m "message"
git push --set-upstream origin task5B

git checkout master
git merge task5B
git push  

Conflict was resolved when User A used git pull before push




