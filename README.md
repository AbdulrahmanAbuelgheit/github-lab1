# delete remote branch
git push origin:test
# delete local branch
git branch -d dev
# list tag
git tag
# delete tag locally
git tag -d v1.4
# delete tag remotly
git push origin --delete v1.0
# git rebase
command used to integrate changes from one branch into another by replaying commits from the source branch on top of the target branch. It creates a cleaner, linear commit history by avoiding merge commits.
--git rebase main
# pull request
allows developers to propose changes from one branch to another, typically for review and collaboration before merging. It provides a structured way to discuss, review, and approve code updates.

![Sample Image](https://th.bing.com/th/id/OIP.eKE8nrMRCK3bdvd62kWJ_wHaEK?w=310&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7)
