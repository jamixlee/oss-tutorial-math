% copy project url from github repository

% open terminal

% run git clone command 
git clone https://github.com/jamixlee/oss-tutorial-math.git

% check the project directory

% make "test.java"

% see 'untracked' message
git status

% add
git add test.java
git satus

% commit
git commit test.java -m "add new file"  % -m: message option
git status

% push
git push origin master
