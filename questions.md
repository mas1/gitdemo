How do you see the files changed within each commit using GitHub Desktop GUI?
-they will show up under 'changes' tab on lefthand side

How do you see the contents of what changed within each file for a commit?
-On the main screen of the desktop app new changes are green and deleted changes are red

How do you revert (backout) a commit?
-to revert or backout of a commit: reset --soft HEAD~1 'soft' retains changes made to files 'HEAD~1' tells git to only go back one commit

What does HEAD refer to in the context of git?
-HEAD is a pointer to the current branch reference, which is in a turn a pointer to the last commit made into the working directory.

