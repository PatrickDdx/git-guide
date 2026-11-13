# 5. Undoing things
Explanation: Which tool you use depends on where the mistake is: not staged yet, staged, or already committed.
Commands: git restore <file> (discard changes), git restore --staged <file> (unstage), git commit --amend (fix the last commit), git revert <commit> (undo a commit safely)
Exercise: Mess up notes.txt and restore it. Then stage a file and unstage it. Finally, commit a typo in the message and fix it with --amend.
Warning box: Mention git reset --hard only as "dangerous, avoid for now."