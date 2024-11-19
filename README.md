# task-4

# task :4 

echo "Temporary changes" >> temp-file.txt

git status

git stash

git stash list

git stash apply

git stash drop

git stash apply stash@{1}
```
git stash -u

git stash apply
```

git rebase main

git rebase --continue

git rebase --abort

git log --oneline

git rebase -i HEAD~3
### 3.Modify the commits by changing pick to one of the following:

+ squash (combine commits)
+ reword (edit commit message)
+ edit (edit commit content)
+ drop (remove commit)

### 4.Example of squashing two commits:

+ Change the second commit from pick to squash and save.
+ Git will combine the commit messages for the squashed commit.

git rebase --continue

git log --oneline

git cherry-pick <commit-hash>

git add .
git cherry-pick --continue

git tag -a v1.0 -m "Initial release"

git tag

git tag -a v1.1 <commit-hash> -m "Bug fix"

git push origin v1.0

git push --tags

git remote add origin https://github.com/username/repo.git

git fetch origin

git branch -r

git pull origin main

git push origin main

git push origin feature-branch

git push origin --delete feature-branch

git clone https://github.com/your-username/repo.git

git checkout -b fix-typo

git add README.md
git commit -m "Fixed typo in README.md"

git push origin fix-typo

git remote add upstream https://github.com/original-owner/repo.git

git fetch upstream

git checkout main
git merge upstream/main

git push origin main