# Pulled from Xtreme-Apps (make sure you thank them for their hard work!)

- add a new app with `.utils/add-subtree.sh <path> <repo url> <branch> [subdir]`, this will pull the history and create `path/.gitsubtree` to remember the url, branch and subdir
- run `.utils/update-subtree.sh <path>` to pull updates for a subtree
- or run `.utils/bulk-update-subtrees.sh` to do it for all subtrees
