# Resolving merge conflicts

In this git repository you'll learn how to resolve a merge conflict.

Checkout all branches

* master
* tobi
* felix

And take a look at all commits to understand what has been done.

Now merge the "master" with "tobi":

  git checkout master
  git merge tobi

Now merge the "master" with "felix":

  git checkout master
  git merge felix

Happy merge conflict fixing.

Now reset master to the "starting-point"

  git checkout starting-point

  git rebase tobi
  git rebase felix

Happy merge conflict fixing.

Understand when you can safely use git push and when you have
to use git push -f.

Understand what git push -f means for your coworkers.

Bonus round:

  git merge strangedude
  git rebase strangedude

