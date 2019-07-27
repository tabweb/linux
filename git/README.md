## linux git

- [git 官方文档](https://git-scm.com/book/zh/v2)
- [github 的 Git 版本发布界面](https://github.com/git/git/releases)
- [Linux 下更新 git 版本](https://blog.csdn.net/qq_19470683/article/details/84140397)
- [linux 下部署 git 服务器](https://www.cnblogs.com/chenglee/p/9766898.html)
- [搭建 Git 服务器](https://www.liaoxuefeng.com/wiki/896043488029600/899998870925664)

```
git clone git@193.112.106.126:/usr/local/gittest.git

ssh-keygen -t rsa -C "tabweb@163.com"

cd C:\Users\用户
ssh git@193.112.106.126 'cat >> .ssh/authorized_keys' < ~/.ssh/id_rsa.pub
ssh git@193.112.106.126 'cat >> .ssh/id_rsa.pub' < ~/.ssh/id_rsa.pub
```

## rgm yum 包管理工具

- [LinuxRPM 包安装](https://www.cnblogs.com/tswhq/p/7868314.html)
- [rgm 包管理工具](https://www.cnblogs.com/mingc/p/7624453.html)
- [yum 包管理工具](https://www.cnblogs.com/mingc/p/7628038.html)
- [Linux 包管理工具（rpm/dpkg，yum/apt，alien）](https://www.cnblogs.com/sonice-cinsy/p/6612887.html)

## linux node

- [Linux 下 Nodejs 安装](https://blog.csdn.net/dwjpeng2/article/details/82994321)

```
wget http://nodejs.org/dist/latest/node-v10.11.0-linux-x64.tar.gz
tar  xf node-v5.10.1-linux-x64.tar.gz -C /usr/local/
cd /usr/local/
mv node-v5.10.1-linux-x64/ nodejs
ln -s /usr/local/nodejs/bin/node /usr/local/bin
ln -s /usr/local/nodejs/bin/npm /usr/local/bin
```

> 像上图中红色框里面的就是已经编译好的文件，选择好对应的 linux 版本下载即可，简单说就是解压后，在 bin 文件夹中已经存在 node 以及 npm，如果你进入到对应文件的中执行命令行一点问题都没有，不过不是全局的，所以通过建立软链接的方式将这个设置为全局就好了。

## yum

| yun 命令        | 说明           |
| --------------- | -------------- |
| sudo yum update | 首先先更新系统 |
| yum remove git  | 卸载 git       |
