# git使用文档

## 1、简介

git是个分布式版本管理工具，与集中式版本管理工具svn相反。

## 2、下载

**官网：** https://git-scm.com/downloads

## 3、安装

省略

## 4、远程仓库配置(gitHub)

省略

## 5、配置SSH

### 5.1用户名

```shell
 git config --global user.name "tututuyang"

```

### 5.2邮箱

```shell
git config --global user.email "1090697389@qq.com"
```

### 5.3 生成SSH（以有SSH可以跳过这一步)

```shell
 ssh-keygen -t rsa -C "1090697389@qq.com"
```

SSH文件存放在C:/User/用户/.ssh下，id_rsa为私钥，id_rsa.pub为公钥。

### **5.4 github配置SSH**

​	打开id_rsa.pub文件，全选，复制全文

​	github->账户->setting

