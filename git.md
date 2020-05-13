Push commits over to new git remote branch but doesn't work
```
$ git status
# On branch master
nothing to commit, working directory clean
```

Need to push it again and this will add any newly created contents
```
$ git push --set-upstream git@gitlab.com:module/myproject.git master
Counting objects: 26, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (20/20), done.
Writing objects: 100% (26/26), 10.72 KiB | 0 bytes/s, done.
Total 26 (delta 1), reused 0 (delta 0)
To git@gitlab.com:module/myproject.git
 * [new branch]      master -> master
```

