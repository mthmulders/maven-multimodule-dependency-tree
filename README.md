# Maven multi-module dependency tree
In a multi-module Maven project, you want to analyze your dependency tree.
This doesn't work by default.

Current work-arounds:

1. You must either install the project to your local repository.
1. You must deployed the project to a remote repository.

But you should be able to run `dependency:tree` without either those.
