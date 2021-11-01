### 

```
0 配置公钥
  (1) cd ~/.ssh
  (2) ssh-keygen -o
  (3) cat ~/.ssh/id_rsa.pub
1 创建项目(项目自带有git仓库)
2 在远程创建仓库
3 本地仓库和远程仓库需要进行关联
  git branch -a // 查看本地和远程的所有仓库
  vue create project创建项目后，仓库还没有和远程进行关联，远程是没有关联仓库的
  1 git remote add origin git@github.com:lanlianhua231986/2109.git
    git push -u origin master  把代码推送到远程
  2 本地仓库已经和远程仓库关联过了,但是现在我们需要推送到新建的仓库里面
    (1)解除和远程仓库的关联  git remote reomve origin
    (2) git remote add origin git@github.com:lanlianhua231986/2109.git 和远程进行关联
        git push -u origin master  把代码推送到远程
```

