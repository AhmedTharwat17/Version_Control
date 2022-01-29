Pull Reguest : 
A pull request is a method of submitting contributions to an open development project.
It is often the preferred way of submitting contributions to a project using a distributed
version control system (DVCS) such as Git. A pull request occurs when a developer asks for changes committed to an external 
repository to be considered for inclusion in a project’s main repository.
.........................................................................................................................................
git revert This is a safe way to undo changes, as it has no chance of re-writing the commit history,
The use of git revert is to create a new commit which reverts a previous commit,
The HEAD will point to the new reverting commit.
.........................................................................................................................................
git restore git restore is to restore the things happened in the working tree so restore files not restore branch
..........................................................................................................................................
Git Reset : 
if i have 5 commits , and then i found that the last two commits are bad and i wanna back to my number 3 commit , and i wanna number 3 commit to be my head ,
so i will use git reset , but the disadvanage of that i will lose number 4 and 5 comiitts
