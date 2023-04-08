`to push all branches to new account repo`

```git remote add new-origin <new-repo-url>```
```for remote in `git branch -r | grep -v master `; do git checkout --track remotes/$remote ; done```
```git push --all```
