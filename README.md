# yunf
only Test

### 基本使用

进入仓库文件夹（若没有、需创建一个目录当仓库地址）、初始化仓库

```apl
git status	//查看仓库状态
git init	//初始化仓库

git add 文件	//把文件存放再暂存区
git commit -m "文件备注"

git log		//仓库提交日志
git branch	//仓库分支
git checkout	//切换分支
//在某一分支下创建分支A，并进入分支B		分支A和分支B可以是一样
git checkout -分支名A -分支名B
//在当前分支下，将分支名合并到当分支
git merge 分支名
git branch -d 分支名		//删除分支
git tag 标签名（例如v1.0)		//给当前所在分支打上标签

```

### ssh

本地生成ssh密钥，在github中添加

Git绑定ssh -T git@github.com

```
把文件推（上传）到Github远程仓库中
git push origin master
把文件拉（下载）到Github本地仓库中
git pull origin master
```

### SSH获取代码

在Github中获取Https地址

```
git clone Https地址
```

### 向仓库提交文件

git push origin master		第一次需要账号密码进行验证，直接关联GitHub账号即可

### 注意事项

有时不能git add时，需要git init
