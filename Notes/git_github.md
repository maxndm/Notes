
# Github and git
- Git is version control system
 ![alt text](git_pic.png "Title")
- Git commands
  -  __git clone__ - bring a repository hosted somewhere, for example Github, into a folder on local machine
  -  __git init__ - initializes git repository
  - __git status__ - Gets status of local repository
  - __git add \<file\>__ - track files and changes in Git - new files
  - __git commit \-m "created file(message)" -m "description"__ - save your files in Git
  - __git push origin main__ - Upload Git commits to remote repository, for example Github.
  - __git pull__ - Download changes from remote repository to local machine
  - __git log__ - gets all commits
  - __git branch \<name\>__ - creates a new branch \<name\> - without name it will print all the branches
  - __git checkout \<name\>__ - switches branch \<name\>
  - __git checkout \<target\>__ and __git merge \<branch\>__ - merges desired branches into target branch
  - __git branch -d/-D \<name\>__ - remove branch
  - __git stash push__ | __git stash list__ | __git stash apply__ | __git stash pop__ | __git stash clear__ - save changes but remove from branch - by applying it applies to branch but stays in stash - by popping it applies and removes from stash

- SSH key
  - is used to identify myself as owner of remote repository
  - ssh-agent setup https://www.cyberciti.biz/faq/ubuntu-18-04-setup-ssh-public-key-authentication/
  - better ssh-agent setup https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
  