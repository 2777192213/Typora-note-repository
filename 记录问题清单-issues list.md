# 记录问题清单-issues list

## 保护分支设置

第一步：找到代码管理库中设置

![image-20230927100955966](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20230927100955966.png)

第二步：设置保护分支（注意推送规则一定为无）

![image-20230927103703193](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20230927103703193.png)



设置保护分支情况下，第一版本后再次将代码提交到master上时。应急解决方案：

```shell
1、代码回滚

2、选择之前的版本commit_id

3、执行命令： git reset --hard <commit_id>

4、执行完后，强制推送： git push -f
```

![image-20231117154953517](记录问题清单-issues list.assets/image-20231117154953517.png)
