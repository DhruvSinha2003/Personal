git init 

Dhruv@DhruvLenovo MINGW64 ~/Desktop/Coding/Personal (master)
$ git add .
warning: in the working copy of 'WAD/Assignment 1 A/.vscode/settings.json', CRLF will be replaced by LF the next time Git touches it
warning: in the working copy of 'WAD/Assignment 1 A/index.html', CRLF will be replaced by LF the next time Git touches it
warning: in the working copy of 'WAD/Assignment 1 A/style.css', CRLF will be replaced by LF the next time Git touches it
warning: in the working copy of 'WAD/Assignment 1 B/data-list.html', CRLF will be replaced by LF the next time Git touches it
warning: in the working copy of 'WAD/Assignment 1 B/index.html', CRLF will be replaced by LF the next time Git touches it
warning: in the working copy of 'WAD/Assignment 1 B/test/index.html', CRLF will be replaced by LF the next time Git touches it


Dhruv@DhruvLenovo MINGW64 ~/Desktop/Coding/Personal (master)
$ git commit -m "Added git files"
[master 968dc5e] Added git files
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 WAD/Assignment 2/github

Dhruv@DhruvLenovo MINGW64 ~/Desktop/Coding/Personal (master)
$ git branch -M main

Dhruv@DhruvLenovo MINGW64 ~/Desktop/Coding/Personal (main)
$ git push -u origin main
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

Dhruv@DhruvLenovo MINGW64 ~/Desktop/Coding/Personal (main)
$ git remote -v

Dhruv@DhruvLenovo MINGW64 ~/Desktop/Coding/Personal (main)
$ git remote add origin https://github.com/DhruvSinha2003/Personal.git

Dhruv@DhruvLenovo MINGW64 ~/Desktop/Coding/Personal (main)
$ git remote get-url origin
https://github.com/DhruvSinha2003/Personal.git

Dhruv@DhruvLenovo MINGW64 ~/Desktop/Coding/Personal (main)
$ git push -u origin main
Enumerating objects: 23, done.
Counting objects: 100% (23/23), done.
Delta compression using up to 8 threads
Compressing objects: 100% (17/17), done.
Writing objects: 100% (23/23), 8.23 MiB | 2.76 MiB/s, done.
Total 23 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/DhruvSinha2003/Personal.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
