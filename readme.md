# check about remote urls or sources from where we can push and pull
```cmd
 $. git remote -v
```

# we can add the remote source as
```cmd
 $. git remote add "source_name" "your_url"
```

# push the changes to github or any other service
```
 $. git push "source_name" "branch_name"
 ex: git push origin main
```

# upstream branch 
```
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main --> meaning if we push from main it will we pushed to origin 

    we can also use -u to set upstream branch
    git push -u origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.
```