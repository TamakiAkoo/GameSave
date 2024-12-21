# GameSave
游戏存档
# 远程和本地分支关联
-  git init
-  git remote add origin https://github.com/TamakiAkoo/GameSave.git (origin 是 远程分支的别名)
-  git fetch origin (同步远程分支信息，要不然关联到别的分支就会失败只能关联到master ，这样就可以关联到别的分支上去了) 
-  git checkout -b EldenRing origin/EldenRing
  - git checkout -b feature-branch origin/feature-branch
  - 创建一个本地分支 feature-branch。
  - 将该本地分支设置为跟踪远程仓库的 origin/feature-branch 分支。 
