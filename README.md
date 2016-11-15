
# Git

[Undo commits permanently](https://git-scm.com/docs/git-reset)

```
$ git commit ...
$ git reset --hard HEAD~3
```

The last three commits (HEAD, HEAD^, and HEAD~2) were bad and you do not want to
ever see them again. Do not do this if you have already given these commits to somebody else.

