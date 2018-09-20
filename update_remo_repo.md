# Reference: 
* http://www.blackdogfoundry.com/blog/moving-repository-from-bitbucket-to-github/
* http://www.paulund.co.uk/change-url-of-git-repository

```
$ cd $HOME/Code/repo-directory
$ git remote rename origin bitbucket
$ git remote add origin https://github.com/mandiwise/awesome-new-repo.git
$ git push origin master
$ git remote rm bitbucket
```
