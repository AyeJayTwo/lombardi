Commits to this repository are welcome (and encouraged!)

### To contribute: 
* fork this repository
* create a branch (with a descriptive name!) on your forked repo
* build something cool (or squash a bug)
* merge lombardi/master (in case things have changed)
* submit a pull request

### Or, put another way:
* click fork
* `git clone https://github.com/<your-github-username>/lombardi.git`
* `git remote add upstream https://github.com/blattus/lombardi.git`
* `git checkout -b my_awesome_branch`
* build something cool (or squash a bug)
* `git add . && git commit -am "descrptive commit message describing what the change does"`
* `git merge upstream master`
* (work through any change issues, if applicable)
* submit a pull request 

### A few guidelines:
* While there isn't a test suite as of yet, it's highly recommended that you test any changes locally using your own instance of Slack. You can see how to set this up in the [Wiki](#wikilnk).
* When possible, reference [issue](#issuelink) numbers in commit messages so things stay linked on GitHub
* Use the code as the subject in commit messages (e.g., say that a branch "fixes #3" or "closes #15" versus you "fixing #3")