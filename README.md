# learnGit

保留早期branch.md中的[教程](https://learngitbranching.js.org/)

Everything up-to-date.


## use
+ 正常使用push时突然报这个错， 用`ssh -T git@github.com`检查是正常的。过了几分钟发现可以正常git push了。 猜测是github服务器22端口重启的原因
```
ssh: connect to host github.com port 22: Connection timed out
fatal: Could not read from remote repository.
Please make sure you have the correct access rights and the repository exists.
```