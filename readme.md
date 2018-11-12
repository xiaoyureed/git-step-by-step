# git step by step

```sh
# init
#  create readme & resources dir & .gitignore(暂时排除readme的影响)
➜  git-step-by-step git:(master) touch readme.md
➜  git-step-by-step git:(master) ✗ mkdir resources
➜  git-step-by-step git:(master) ✗ touch .gitignore
➜  git-step-by-step git:(master) ✗ ls
readme.md  resources .gitignore
➜  git-step-by-step git:(master) ✗ echo resources > .gitignore
➜  git-step-by-step git:(master) ✗ echo .gitignore >> .gitignore
# add all files to Index area
➜  git-step-by-step git:(master) ✗ git add .
➜  git-step-by-step git:(master) ✗ git commit -m "init"
[master (root-commit) cdb304f] init
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.md

# now, let's create a file naming "file1"


```