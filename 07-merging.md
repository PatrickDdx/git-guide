# 7. Merging & conflicts

Explanation: Merging brings changes from one branch into another. A conflict happens when both branches changed the same line, so Git asks you to decide.

Commands: git merge <branch>, then edit the file, git add, git commit

Exercise: Merge feature-shopping-list into main. Then cause a conflict on purpose: change the same line of notes.txt on two branches, merge, and resolve the <<<<<<< / >>>>>>> markers.