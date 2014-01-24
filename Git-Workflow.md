#Git Workflow
> Inspired by Vincent Driessen's [git-flow branching model](http://nvie.com/posts/a-successful-git-branching-model/)

##Naming conventions

####Branches
* **feature branches** - used for active development. The naming convention is ``feature/FEATURE_NAME``  
* **bugfix branches** - quick fixes off of master. The naming convention ``bug/BUG_NAME``  
* **experiment branches** - used for experiments during development. The naming convention is ``experiment/EXPERIMENT_NAME``  
* **master** - the central branch of the repository. 

####Tags  
> Tags are used to capture development milestones.

* **release tags** use the naming convention ``release/VERSION_NUMBER``  
* **review tags** use the naming convention ``review/REVIEW_DATE``

##Best practices
* **Commit related changes** - Each commit should be a wrapper for related changes. Avoid including multiple features or bugfixes in a single commit.
* **Keep master conflict free** - Before merging work into master, merge master into your branch to resolve any conflicts first.
* Don't commit large binary files.
