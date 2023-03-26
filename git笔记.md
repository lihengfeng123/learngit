

git init                                      在当前目录为git仓库

git commit -m "注释"

git status                                 查看当前仓库状态

git reset  --hard 版本号         恢复

git log 

git diff 文件                           查看修改的地方

git reflog                                 查看文件

git branch dev                          创建分支

git switch dev							切换分支

git rm test.txt							删除文件							

git stash                                   保存状态

git stash apply                          恢复状态

git stash pop                                 恢复并删除状态

git stash drop                             删除状态

git stash list                               列出状态

git cherry-pick 4c805e2             合并

git tag v1.0                                 创建标签

git show v1.0                              展示标签

git tag -a v1.0 -m ""                    给标签添加说明

git tag -d v1.0                                 添加标签

push orign --tags                              推送



解决：Warning: Permanently added ‘github.com’ (ED25519) to the list of known hosts.
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

问题是密钥不对

检查是否有**`id_rsa、id_rsa.pub`密匙**

ls ~/.ssh

ssh-keygen -t ed25519 -C "xxx@xxx.com" 生成新的密钥



