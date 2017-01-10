# Files

Search a word in a file
```
$ grep -c '\<word\>' file.csv
```

# Markdown

Compile Markdown to HTML
```
$ npm install -g marker
$ marker -i file.md -o file.html --gfm
```

# Network

IP address for the first network service
associated with the given interface (`en0` in the example)
```
$ ipconfig getifaddr en0
```

# Recipe for a new js module

```
$ git clone git@github.com:riccardoscalco/outset-js-module.git my-new-module
$ cd my-new-repo
$ rm -rf .git

Create a repo on Github
$ git init
$ git ..

$ npm install xo
Edit...
$ npm publish
```


# Git

[Undo commits permanently](https://git-scm.com/docs/git-reset)

```
$ git commit ...
$ git reset --hard HEAD~3
```

The last three commits (HEAD, HEAD^, and HEAD~2) were bad and you do not want to
ever see them again. Do not do this if you have already given these commits to somebody else.

