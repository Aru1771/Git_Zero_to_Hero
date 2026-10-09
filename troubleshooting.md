Got issues:

authentication issue:
----------------------

1. issue with ssh_url

solution1: issue with ssh_url
1. first i have connect with http url and removed the repo entry and again i connected with ssh_url.
2. then i have faced the below error message:
   
       See git-pull(1) for details.
    
        git pull <remote> <branch>
    
        If you wish to set tracking information for this branch you can do so with:
    
        git branch --set-upstream-to=origin/<branch> main


3. to reolve this issue:

          Update remote to SSH: git remote set-url origin git@github.com:Aru1771/Jenkins-Zero-To-Hero.git

           
          Set upstream tracking for your branch: git branch --set-upstream-to=origin/main main or git push -u origin main (The -u flag sets upstream automatically.)
          
