# git-github-pull-request
How to contribute open source / How To Pull Request

```
    git clone git@github.com:mir-owahed/git-github-pull-request.git
    cd git-github-pull-request/
    code .
    git branch
  242  git log
  243  git status
  244  git branch git-pr
  245  git branch
  246  git checkout git-pr
  247  git branch
  248  git log
```
You can update into new branch

```
250  git status
  251  git add .
  252  git commit -m "git PR step by step guide added"
  253  git remote -v
  254  git push -u origin git-pr
```
```
remote: Create a pull request for 'git-pr' on GitHub by visiting:
remote:      https://github.com/mir-owahed/git-github-pull-request/pull/new/git-pr
remote: 
To github.com:mir-owahed/git-github-pull-request.git
 * [new branch]      git-pr -> git-pr
Branch 'git-pr' set up to track remote branch 'git-pr' from 'origin'.
```
### Git PR
```
git branch
  247  git checkout -b git-pr-test
  248  git branch
  249  git add .
  250  git commit -m "markdown syntax added"
  251  git push
  252  git push --set-upstream origin git-pr-test
  
```



