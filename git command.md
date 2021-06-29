###  git常用命令

#### 设置用户名和密码

```git 
git config --global user.name 'your user name'

git config --global user.email 'your email'
```

#### 提交代码

```git
git add .
git status 
git commit -m 'message'

```

####  设置git本地用户名密码

```git
git config --global credential.helper store
```

上面这个该命令会在你本地生成一个文本，上边记录你的账号和密码。

然后接下来，再操作一次git pull或者git push命令，然后此时会提示输入用户名和密码，这一次输入以后，以后就不需要再次输入用户名和密码啦！
