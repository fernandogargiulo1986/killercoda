#### Solution

`cd ~/repo/local_working_dir/project`{{execute}}
`git checkout new_branch`{{execute}}
`echo "print('Buongiornissimo')" >> new_new_feature.py`{{execute}}
`git add new_new_feature.py`{{execute}}
`git commit -m "Commit we will regret"`{{execute}}
`git push origin new_branch`{{execute}}
`git revert HEAD`{{execute}}
`git status`{{execute}}
