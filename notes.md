# Pro Git Notes

| Command | Description |
| - | - |
| git init | start tracking an existing project |
| git clone url foldername | clone repo at url into a folder |
| git status -s / --short | get status in short format | 
| git commit -a -m "message"| stage and commit all changes at once |
| git rm filepath | remove a file and stage |
| git rm --cached filepath | remove file from staging area |
| git mv file_from file_to | rename a file |
| git log -p -2 | display log with diff for the last 2 commits |
| git log --stat | display log with stats for each commit (files changed, lines added/removed)
| git log --pretty=oneline/short/full/fuller | display log in short format |
| git log --pretty=format:"..." | display log using custom format |
| git log --pretty=format:"%h %s" --graph | display history graph |
| git log --grep=\<pattern\> | display logs where messages contain \<pattern\> |
| git log -S\<string\>| display logs that cantain provided string in their change |
| git log -- filepath | display logs that affect provided path only |
| git remote -v | list this project's remotes together with their URLs |
| git remote add URL | add a remote repo |
| git tag | list all available tags |
| git tag -a \<tagname\> -m "message" | create an annotated tag with \<tagname\> and message -> `git tag v1.1 -m "Release 1.1"` |
| git show \<tagname\> | display a tag data |
| git tag \<tagname\> | create a lightweight tag | 
| git push origin \<tagname\> / --tags| to push a tag / all tags to remote | 
| git log --decorated | display branch pointer next to commit it points at |
| git merge \<branch name\> | merge given branch into the current one |
| git branch -d \<branch name\>| delete given branch |