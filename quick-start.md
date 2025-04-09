# 快速开始

## Windows

* ### 首先确保本地已安装新版QQ

```
https://dldir1.qq.com/qqfile/qq/QQNT/Windows/QQ_9.9.18_250318_x64_01.exe
```

* ### 下载并解压NC-Medic程序包

```
NC-Medic
├──launch-user.bat //启动脚本
├──...
├──dic
│   ├──...
│   └──hdic.txt //词库文件
└──config
    ├──...
    └──admin.json //权限配置
```

* ### 添加主人权限

> 打开config/admin.json，将主人QQ设为true

```js
{ 
    "主人QQ": true 
}
```

* ### 启动

```
//正常启动
launcher-user.bat

//快速登录
launcher-user.bat qq号
```

## Linux

!> 建设中

## 使用词库

> 默认词库文件夹为dic，主词库文件为hdic.txt<br>
> 在hdic.txt中增删修改并重新载入，实现bot的实际功能<br>
> 你可以学习如何[编写词库](write-dic)，成为开发者 

