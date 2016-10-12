Javascript frameworks in the Batcave
------------------------------------
##100 things to know about front end javascript workflows

It's time to take the next step in front end workflows. In the following writeup I hope to explain the general landscape of front end development tools.

1. Git
  * __Git init__
  * __Git config --global user.name || git config --global user.email__ || git config --global color.ui true || git log --pretty=oneline || git log --pretty=format:"%h %ad- %s [%an]" || git log --oneline -p || git log --oneline --stat || git log --oneline --graph || git config --list
  * __Git status__
  * __Git add .__ || __Git add --all__
  * __Git commit -m "Initial commit"__
  * _shortcut_: git commit -a -m "Add and commit"

  * __Git remote add origin git@github.com:megomars/WorkflowsInTheBatcave.git__
  * Git remote show origin || git remote -v || git remote rm origin //removes remote
  * __Git push -u origin master__ //push to a remote
  * Git pull // pull from github

  * Git log
  * Git diff || Git diff --staged // View staged differences
   _UNSTAGE CHANGES_
  * Git reset HEAD <file>
  _DISCARD CHANGES_
  * Git checkout -- <file>
  _UNDO COMMIT_
  * Git reset --soft HEAD^
  _UNDO LAST COMMIT AND ALL CHANGES_
  * Git reset --hard HEAD^ || Git reset --hard HEAD^^ //last two commits
  _AMMEND COMMIT_
  * Git commit --amend -m "Amended file"


  * Git clone git@github.com:megomars/WorkflowsInTheBatcave.git
  * Git branch beans // new beans branch
  * Git checkout beans // work on beans
  * Git checkout master
  * Git merge beans
  * Git branch -d cat
  * Git checkout -b beans == same as git branch beans and then git checkout beans

  * Git fetch // Fetch (or Sync) our local repository with the remote one
  * Git merge origin/master

  * Git branch -r // list all remote branches
  * Git push origin :shopping_cart // remove remote branch
  * Git remote prune origin // clean up deleted branches

  * git tag
  * git tag -a v0.0.3 -m "version 0.0.3" // add new tags
  * git push --tags // push new tags

  * git rebase
  * git blame index.html --date short
  * vim .gitignore // add files to ignore there


2. Node js
  * Node is a platform for running Javascript applications
  * Uses async event base model for a single thread
  * Node Plugins

3. NPM
  * package.json
  * npm install // install stuff from someones github repo after cloning

4. Yeoman (Yo, Grunt, Bower)
  * Yo is a scaffolding tool for firing up ready to use templates
  * Grunt/Gulp is a task runner for performing automated tasks
  * Bower is a package manager for front end dev dependencies

  * npm install -g yo
  * yo webapp
  * npm update -g yo
  * always work in app folder
  * writing tests // TDD, Mocha, Chai, Jasmine

  * gulp //run the project
  * gulp serve //development build

5. Writing Clean Javascript
  * Name everything as clearly as possible
  * Add comments where necessary
  * Keep functions close to each Other
  * Modularize your files
  * SRP===DRY (don't repeat yourself && Single responsibility principle)

6. RequireJS

7. Jasmine

8. JSHint

9. Modernizr

10. Handlebars

11. Scrum

Other
--------------
 Unit testing
 Scrum
 Best practices
 TDD
 Browser testing
