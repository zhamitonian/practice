Some usually use command of git.
git status   % check status of file 

% get file from github
git colon 'ssh key'

% upload file to github
git init 
git remote 'ssh key'
git remote -v  % check 
git push -u origin master     % -u,you can use just 'git push' to do the same thing.
git commit -m '' -m ''

%% branching
git branch  % check your branch;* you currently on
git checkout -b new_branch  % create new branch
git checkout master  % switch to master branch
git diff new_branch % compare new_branch with master
git push -u origin new_branch  % upload new_branch to github
%%after merge,git pull to get the latest version of the code.
%% git branch -d new_branch  % delete new_branch
% when only one file is changed, you can use git commit -am "commit message" to commit the change.