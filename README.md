# first
first create repository
# 今天学习了MarkDown

MarkDown是一种超文本语言，今天我第一次学习了它。
```hello MarkDown!```

接下来我还会学习:
1. Git的基础命令
1. Hexo框架
1. Hexo更换主题

用命令行是一种**Geek**行为,我觉得还挺有趣的。

```Geek是指极客，通常被用于形容对计算机和网络技术有狂热兴趣并投入大量时间钻研的人。所以俗称发烧友或怪杰。```

有点意思，下面这张gif可以形容我的心情:

![](https://qgt-style.oss-cn-hangzhou.aliyuncs.com/newcoursep4/g1/g1-2-2/tenor.gif)

```cat ~/.ssh/id_rsa.pub```

这条指令来查看自己的ssh是否配置

全局变量设置

在第一次使用git时,git会提醒进行全局变量的配置

```git config --global user.name "peng"```

```git config --global user.email "hhdd576@126.com"```

git clone的语法非常简单

```git clone 仓库地址``` 

仓库地址在github上找到

# 常见的linux命令

查看目录下的文件

```ls```

在当前目录下创建文件

```touch 文件```

在当前目录下创建文件夹

```mkdir 文件夹```

进入某个文件夹

```cd 文件目录```

删除当前目录下的文件

```rm -rf 文件名```

# git提交的三部曲

git提交一般分为三步

1. git add
1. git commit
1. git push

# git add

```git add -A```

# git commit

```git commit -m "备注"```

# git push

第一次提交

```git push origin master```

第二次到第n次

```git push```

提交到其他的分支

```git push origin b```

查看当前绑定的仓库

```git remote -v```

初始化为git仓库

```git init```

仓库地址

```git remote add origin + 仓库地址```

查看绑定的情况

```git remote -v```

创建博客文件夹

```hexo init blog```

## 安装博客工具

打开terminal 输入下列指令:

```npm install hexo-deployer-git --save```

## 修改配置文件

进入博客文件夹找到 _config.yml 这个文件，打开输入配置

```
theme: landscape

deploy:

  type: git

  repository: 你的GitHub仓库地址

  branch: master
```

## Hexo提交

Hexo的提交也分为三个部分

1. hexo clean
2. hexo generate
3. hexo deploy








