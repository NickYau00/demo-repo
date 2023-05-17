# Demo

Some description!

## Subheader

Watch tutorial on YouTube.

## Notes from the video

Git is a Version control system (free and open source).
CLI - Command Line Interface
Code Editor - Word Processor for Writing Code
Repository - A place where your projects are stored
Github - A website to host your repositories online

Git Commands
clone - Bring a repository that is hosted somewhere like Github into a folder on your local machine
add - Track your files and changes in Git
commit - Save your files in Git
push - Upload Git commits to a remote repo (eg Github)
pull - Download changes from remote repo to your local machine

(8:50) Create a readme file on Github
README.md - md stands for markdown, an easy way to format your text
'#' for header
'##' for subheader

(13:30) Using VS Code
Explorer (Crtl+Shift+E) -> Open Folder -> open the relevant folder to add files and folders.

Pull repo on Github to local system using Git.
Access terminal >> View -> Terminal (Crtl+`)
'ls -la' does not work in Windows!
git clone [https from Github]

git status - shows files that were updated/created/delete, but haven't been saved in a commit yet (shows in RED).
'Untracked files' - Git doesn't know about the files yet. To track files, use 'add' command.

git add [specify a filename or use '.']
Usually just use git add . to track all changes, including the untracked and modified section.
Use git status again the files should now show in GREEN, meaning they are ready for commit.

(19:18) Committing
git commit -m "[need a message]" -m "[can add description]"
after git commit, the files are only saved locally, they are not on GitHub yet!
git push to save in GitHub
