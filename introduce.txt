#git init //shortcut create folder
#git add <filname , *lastname , . > //tracked bring file to staging area
#git commit -m(Messange) " Messange " //bring file from staging area to local
#git rm --cached <filename> //untracked
#git log --oneline/graph //straight meaning
#git checkout <filename> //respaw
#git diff <commitId to prepare>
#git reset --hard <commitId> //bring to this version and delete the left of version
#git reset --mix <commitId> //bring to this version and untracked(working directory)
#git reset --soft <commitId> //bring to this version and unadd(staging area)