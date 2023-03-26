

git init                                      在当前目录为git仓库

git commit -m "注释"

git status                                 查看当前仓库状态

git reset  --hard 版本号         恢复

git log 

git diff 文件                           查看修改的地方

git reflog                                 查看文件

git branch dev

git switch dev

git rm test.txt

解决：Warning: Permanently added ‘github.com’ (ED25519) to the list of known hosts.
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

问题是密钥不对

检查是否有**`id_rsa、id_rsa.pub`密匙**

ls ~/.ssh

ssh-keygen -t ed25519 -C "xxx@xxx.com" 生成新的密钥



