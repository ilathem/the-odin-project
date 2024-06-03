## What is a safe way to push history changes to a remote repository?

Make sure that everyone who uses the repository knows that you are 
changing the history, and use the default `git push` or 
`git push --force-with-lease` option to check and make sure that the branch 
you are pushing to does not have any further updates.

## What are the dangers of history-changing operations?

You can potentially destroy yours and other contributors' work, wasting time
and effort.

## What are best practices of history-changing operations?

Make sure everyone knows you are changing the history, only change local
history, only change history on your own branches, and don't push after
every single commit.
