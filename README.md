# Git Commands in 60 seconds

## This repository is used for a video

### - `git init`

&nbsp;&nbsp;&nbsp;&nbsp;used for initialization of an git version control project.

### - `git add`

- `(*)`
  - `(*)` is used to stage all the files in the folder you are currently in.
- `<file-name>`
  - `<file-name>` is used to stage the changes of one file.
  - `IMPORTANT:-` replace <file-name> with the file name with the file extention to stage it.
  - `REMEMBER:-` Will be used after the `git init` command.

&nbsp;&nbsp;&nbsp;&nbsp;
This is used for which files and folder to commit, etc, what is commit explained in next's next command.

### - `git status`

&nbsp;&nbsp;&nbsp;&nbsp;git status is used to determine which file is updated, staged and pushed.

### - `git commit`

- `-m "<commit-message>"`
  - use -m to simply type any message inside the Double Quotes ("")
  - `IMPORTANT:-` replace <commit-message> with your message, message could be the features you add, etc...
  - `REMEMBER:-` should be used after `git add` command.

&nbsp;&nbsp;&nbsp;&nbsp;
This is used to commit any important changes if your application or website breaks you can use the next command to get the working version back, and use the -m to save time if you just do git commit it will open a vim editor you have to type in the message and press these keys `ESC + : + W + Q` don't press the + These are for ilustration purpose that you have to type that also `ESC` is the escape key which should be on the top right corner of the keyboard, if you don't want to commit a file then just go and create a .gitignore file and in that file add the file name with file extention init

### - `git log`

&nbsp;&nbsp;&nbsp;&nbsp;git log is used to log all the commit that are made to the git, and use --oneline flag to get the commit id assigned by Git provider like Github, Gitlab, Bitbucket, etc...

### - `git restore <file-name>`

&nbsp;&nbsp;&nbsp;&nbsp;git reset gives you the commit code at the time the commit id created.