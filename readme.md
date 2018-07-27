## git 仓库管理
### reset
    --soft – 缓存区和工作目录都不会被改变
    --mixed – 默认选项。缓存区和你指定的提交同步，但工作目录不受影响（将你当前的改动从缓存区中移除，但是这些改动还留在工作目录中。）


### checkout
    git checkout HEAD~2
    git checkout 7dc454723f9926c0f0abcdd476c7862140b17bfa
    分离的HEAD，创建新分支，并且上传（快速查看项目旧版本来说非常有用）


    git checkout . 放弃暂存区的修改或者本地修改


### revert
    撤销一个提交的同时会创建一个新的提交
    安全的方法，不会重写历史记录

### merge
    放弃merge git merge --abort
    --hard – 缓存区和工作目录都同步到你指定的提交（完全舍弃你没有提交的改动）
