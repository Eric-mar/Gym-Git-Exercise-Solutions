# Gym-Git-Exercise-Solutions


### Git Basis

## Bundle 1

# Exercise 1

``` bash
PS C:\Users\Cococe Ltd\Desktop\Basis Git> git clone https://github.com/Eric-mar/Git-Exercise-Basis.git .
Cloning into '.'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.
PS C:\Users\Cococe Ltd\Desktop\Basis Git> git branch -M master
PS C:\Users\Cococe Ltd\Desktop\Basis Git> git branch          
* master
PS C:\Users\Cococe Ltd\Desktop\Basis Git> git branch -M main
PS C:\Users\Cococe Ltd\Desktop\Basis Git> git branch        
* main
PS C:\Users\Cococe Ltd\Desktop\Basis Git> git add .\README.md
PS C:\Users\Cococe Ltd\Desktop\Basis Git> git commit -m "starting project"
[main eb4040a] starting project
 1 file changed, 3 insertions(+), 1 deletion(-)
PS C:\Users\Cococe Ltd\Desktop\Basis Git> git push 
fatal: unable to access 'https://github.com/Eric-mar/Git-Exercise-Basis.git/': Recv failure: Connection was reset
PS C:\Users\Cococe Ltd\Desktop\Basis Git> git push 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 291 bytes | 291.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Eric-mar/Git-Exercise-Basis.git
   6287648..eb4040a  main -> main
PS C:\Users\Cococe Ltd\Desktop\Basis Git> git switch -c dev
Switched to a new branch 'dev'
PS C:\Users\Cococe Ltd\Desktop\Basis Git> git switch -c test
Switched to a new branch 'test'
PS C:\Users\Cococe Ltd\Desktop\Basis Git> git checkout dev
Switched to branch 'dev'
PS C:\Users\Cococe Ltd\Desktop\Basis Git> git branch -D test  
Deleted branch test (was eb4040a).
PS C:\Users\Cococe Ltd\Desktop\Basis Git> git status
On branch dev
nothing to commit, working tree clean
PS C:\Users\Cococe Ltd\Desktop\Basis Git> 

```