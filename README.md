# 2023-09-11-git_history
- 'General stuff'
    - 'add <FILENAMES>' adding the <FILENAMES> to the staging area
    - 'commit -m "MESSAGE": commit with a message everything in the staging area
    - 'push <WHERE> <WHAT>': pushes the history/commits to the remote (where) using the commits from the specified branch (what)
    - 'pull <WHERE> <WHAT>': pulls (updates) the local repo with contents in the remote (where) using the information in the specified branch (branch)

- 'log': shows the log
    - 'log -- oneline': shows the log in condenced format
    - this may open a terminal program called 'less' that lets you scroll.
    - press q in terminal to get the prompt back

- 'diff': shows you the "difference" between your changes and the last known git status
    - 'git --stated': shows the diff of the files in the staging area

- 'restore --staged <FILE>': unstages <FILE> from the staging area