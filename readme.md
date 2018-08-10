
# **_Git Assignment_**

**Git task**                               **commands**

**Tell Git who you are**                   git config --global user.name "Sam Smith"  , git config --global user.email sam@example.com

**Create a new local repository**          git init

**Check out a repository**                 git clone /path/to/repository

**Add files**                              git add <filename> , git add *

**Commit**                                 git commit -m "Commit message" ,git commit -a

**Push**                                   git push origin master

**Status**                                 git status

**Connect to a remote repository**         git remote -v,  git remote add origin <server>

**Branch**                                 git checkout -b <branchname>
                                           git checkout <branchname>
					   git branch
                                           git branch -d <branchname>
                                           git push origin <branchname>
                                           git push --all origin
                                           git push origin :<branchname>


**Update from the remote repository**    git pull
                                         git merge <branchname>
                                         git diff

                                         git diff --base <filename>

                                         git diff <sourcebranch> <targetbranch>
                                         git add <filename>

**Tags**
                                         git tag 1.0.0 <commitID>
                                         git log
                                         git push --tags origin

**Undo local changes** 	
	                                 git checkout -- <filename>
                                         git fetch origin
                                         git reset --hard origin/master

**Search** 	 	                 git grep "foo()"


