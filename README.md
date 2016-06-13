# supervisor-portable

## 缘由

公司的线上环境不能安装软件，但是有时还是需要supervisor使用，结果没找到不用安装的，网上都是pip安装的，就把代码改了改做了个单机使用的。

## 描述

一个不是安装的supervisor，下载代码然后方便打包到放到你的项目中使用。

## 使用
1. 首先clone代码

    `
    git clone   https://github.com/iuyo5678/supervisor-portable.git
    `

2. 生成默认配置文件

    `
    cd supervisor-portabl
    `
    `
    python supervisor/confecho.py  > test.conf
    `
   
3. 启动程序

    `
    python supervisor/supervisord.py  -c  test.conf
    `
    
4. 观察程序
    
    打开浏览器，http://127.0.0.1:9001,

    账号：user

    密码：123
    
#enjoy it
