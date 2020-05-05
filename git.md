# **Hello World！**

**github免费为每个用户分配了1g的空间使用。**

[TOC]



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
git config --global credential.helper store
```

### 新增代码或修改代码或新增文件的上传到远程仓库的步骤。

```
git add .

git commit -m "message"

git push
```

### 删除废弃文件的步骤。

```
git rm -r
```

### 添加gitignore忽略无须上传的文件。

```
touch .gitignore
```

执行完毕后会在当前目录产生一个.gitignore文件，范本：

/demo1/target/
/demo1/src/test/
/demo1/.idea/
/demo1/.project/
/demo1/.settings/

### 克隆远程仓库。

```
git clone https://github.com/yourGitId/yourRepoName.git
```

### git本地仓库关联之后，无法删除的解决措施。