# Version Control and Collaboration
reason Version control
 - important for software development and documentation work.
 - Avoids the confusion multifle file seems like.

# changes vs snapshot
 - Changes : storing difference between versions.
 - Snapshots: storing a copy each point of project

# installing git
 - Linux/Mac/Windows(check pre-installed version)
   $ git --version
   git version 2.25.1
   $
 - Linux(install on a Debian-based distribution)
   $sudo apt instll git all
 - Mac
   [install](https://git-scm.com/download/mac)
 - Windows-run"Git Bash"
   [install](https://git-scm.com/download/win)

# git config:First-time setup
 - Git configurations are stored in three levels:
    1.System level:--system option.Affects all uses and repositories on the system(administrative)
      file:/etc/gitconfig
    2.Global(user)level:--global option.Affects all repositories of a current user
      file:~/.config/git/config
    3.Local level:--local option.Specific to the current repository
      file:.git/gitconfig

# git command
## initiallizing a repository in an existing directory
 - $ git init
## checking repository status
 - $ git status
## adding a new file to be staged
 - $ git add[file_name]
## adding all files to be staged(tracked)
 - $ git add
## unstaging a file
 - $ git rm --cached[file_name]
## commit
 - $ git commit -m "commit message"
