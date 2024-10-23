git masterclass
---------------

git stash => save changes to be apply later cause of interruption
git stash => generate key
	stash list => list of stashes
	stash pop => get the saved stash
	stash save name_of_stash
	stash apply numebr_of_stash

git restore : restore to previous state
	it is like undo changes ( working directory )
	restore name_of_file ( working to last commit state )
	restore --staged name_of_file ( from staged to working )

**git branch**
	branch -d

## Merges:

`git commit -am "message"`

this is only works when a file is tracked. it means requires one at least `git add `

`git branch -r` : remote branchs

`git merge` for merge a branch from one to another

`git branch --merged` tell us what the branchs are merged to main

`git branch --no-merged` tell us what are the branchs are not merged to main

## Delete merged and unmerged branchs

`git branch -d` branch for deleting a branch

`git branch -D` for forcing the deletion of a branch

## Rebase
