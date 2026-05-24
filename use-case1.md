(base) PS C:\Users\vivek\OneDrive\Desktop\Github Learning\FeatureLearning> git remote add origin https://github.com/VivekCs181066/feature_github_learning
(base) PS C:\Users\vivek\OneDrive\Desktop\Github Learning\FeatureLearning> git remote -v
origin  https://github.com/VivekCs181066/feature_github_learning (fetch)
origin  https://github.com/VivekCs181066/feature_github_learning (push)
(base) PS C:\Users\vivek\OneDrive\Desktop\Github Learning\FeatureLearning> git push -u origin main
To https://github.com/VivekCs181066/feature_github_learning
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/VivekCs181066/feature_github_learning'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
(base) PS C:\Users\vivek\OneDrive\Desktop\Github Learning\FeatureLearning> git pull origin main --allow-unrelated-histories
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (6/6), 1.18 KiB | 100.00 KiB/s, done.
From https://github.com/VivekCs181066/feature_github_learning
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
Auto-merging app.py
CONFLICT (add/add): Merge conflict in app.py
Automatic merge failed; fix conflicts and then commit the result.
(base) PS C:\Users\vivek\OneDrive\Desktop\Github Learning\FeatureLearning> git push -u origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 573 bytes | 573.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/VivekCs181066/feature_github_learning
   22e1cfb..e44ec9b  main -> main
branch 'main' set up to track 'origin/main'.
(base) PS C:\Users\vivek\OneDrive\Desktop\Github Learning\FeatureLearning> 