# Pre Course Git Fu

## Terms for learning Git
 * Repository - Contains all the files that make up a given project.
 * Git - Version Control - A system that records changes to a file or set of files over time so that you can recall specific versions later.
 * Clone - A copy of a repository created locally from source code downloaded from GitHub. This is usually used when contributitions will be made back to the original project.
 * Fork - A copy of a repository made on GitHub that can be than be modified freely without affecting the original. This is usually used when the intent is to develop the project independently.
 * History - A graph of snapshots, known as commits, of the entire repository.
 * Staging - Marking a modified file in it's current version to be added to the next commit.
 * Remote - Version of project that is hosted on the Internet or other network.
 * Commit - A snapshot or revision to a file made to the local repository that that is given a unique ID used to keep track of the changes.
 * Push - Updates the remote repository with the changes made to the local repository in the latest commit.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`