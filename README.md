# git_assignment_HeroVired

Question 1
1. Created a private repo with git_assignment_HeroVired name, and with a README.md file, and main branch as default.
2. Created dev branch with calc.py file, and added the calculator code.
3. Committed the code, and merged it with main.
4. Create first release of the code as v1.0
5. Added Kavitha as a collaborator
6. Created a new branch feature/sqrt, and added sqrt code
7. Committed the code in feature/sqrt branch.
8. Switched to dev branch again to fix the critical bug reported.
9. Added the fixation code, and committed it.
10. Raised a PR to review from Kavitha.
11. Kavitha reviewed the code, and merged to main.
12. Then created another PR from feature/sqrt to merge with main.
13. After merging feature/sqrt to main, created another release with v2.0
14. Finally updated Readme file. :)


Question 2
1. Created a branch lfs
2. Committed and tried pushing. It gave below error
  git push
  Enumerating objects: 4, done.
  Counting objects: 100% (4/4), done.
  Delta compression using up to 8 threads
  Compressing objects: 100% (3/3), done.
  Writing objects: 100% (3/3), 141.16 MiB | 499.00 KiB/s, done.
  Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
  remote: error: Trace: fdd52c4239fadce23ad3752c3c2572bfddf0789a96ea53860d3e5ec08508c7c2
  remote: error: See https://gh.io/lfs for more information.
  remote: error: File lfsData.csv is 333.73 MB; this exceeds GitHub's file size limit of 100.00 MB
  remote: error: GH001: Large files detected. You may want to try Git Large File Storage - https://git-lfs.github.com.
  To https://github.com/prrandheer621/git_assignment_HeroVired.git
   ! [remote rejected] lfs -> lfs (pre-receive hook declined)
  error: failed to push some refs to 'https://github.com/prrandheer621/git_assignment_HeroVired.git'
3. Then used below commands
     git lfs install
     git lfs track "*.csv"
     git add lfsData.csv
     git add .attributes
     git commit -m "Large file commit"
     git push
4. It got successfully pushed.

Question 3
1. 

