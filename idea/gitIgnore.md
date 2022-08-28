## 添加.gitignore

## 误提交.idea文件夹处理
```
# 删除误提交目录
$ git rm -r --cached .idea

# 删除误提交文件
$ git rm --cached .DS_Store

# 通过git status可查看.idea目录下的文件已删除
$ git status

On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        deleted:    .idea/.gitignore
        deleted:    .idea/dbnavigator.xml
        deleted:    .idea/inspectionProfiles/Project_Default.xml
        deleted:    .idea/misc.xml
        deleted:    .idea/modules.xml
        deleted:    .idea/personal.iml
        deleted:    .idea/vcs.xml
# 记得添加.gitignore文件并配置忽略.idea目录
```