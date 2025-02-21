# check-point
qst 1 : mkdir learn_git
qst 2 : cd learn_git
qst 3:echo .> third.txt
qst 4 : git init
qst 5 : git add third.txt
qst 6 :git commit -m "adding third.txt"
qst 7 : git log --oneline
qst 8 : echo .> fourth.txt
qst 9 : git add fourth.txt
qst 10: git commit -m "adding fourth.txt"
qst 11: del third.txt 
qst 12: git add .
qst 13:git commit -m "removing third.txt"
qst 14 : git log
qst 15:git config --global core.pager "cat"
qst 16: git config --global --list
qst 17 : git config --global --list
