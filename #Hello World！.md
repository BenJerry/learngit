# **Hello World！**

## git 命令版：

### 配置全局的邮箱和用户名，log日志中的用户名即改用户名。

​	q: tell me who you are

​	a: 

```
		git config --global user.email "xxx@xxx.xxx"

​	    git config --global user.name "BenJerry"
```

###  第一次执行会询问用户名密码，成功之后就会绑定远程仓库和本地仓库。

```
 git commit -m "message"

 git push
```

### 配置无访问的拉代码和推代码。

```
git config --global credential.helper stor
```

### 上传代码的步骤。

```
git add .

git commit -m "message"

git push
```

