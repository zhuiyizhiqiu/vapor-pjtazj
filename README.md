<p align="center">
    <img src="https://user-images.githubusercontent.com/1342803/36623515-7293b4ec-18d3-11e8-85ab-4e2f8fb38fbd.png" width="320" alt="API Template">
    <br>
    <br>
    <a href="http://docs.vapor.codes/3.0/">
        <img src="http://img.shields.io/badge/read_the-docs-2196f3.svg" alt="Documentation">
    </a>
    <a href="http://vapor.team">
        <img src="http://vapor.team/badge.svg" alt="Slack Team">
    </a>
    <a href="LICENSE">
        <img src="http://img.shields.io/badge/license-MIT-brightgreen.svg" alt="MIT License">
    </a>
    <a href="https://circleci.com/gh/vapor/api-template">
        <img src="https://circleci.com/gh/vapor/api-template.svg?style=shield" alt="Continuous Integration">
    </a>
    <a href="https://swift.org">
        <img src="http://img.shields.io/badge/swift-4.1-brightgreen.svg" alt="Swift 4.1">
    </a>
</center>

# 用vapor构建服务器

首先是配置环境

| Download | Date |
|----------|------|
| [Xcode](https://storage.googleapis.com/swift-tensorflow/mac/swift-tensorflow-DEVELOPMENT-2018-05-10-a-osx.pkg) | May 10, 2018 |
| [Ubuntu 16.04](https://storage.googleapis.com/swift-tensorflow/ubuntu16.04/swift-tensorflow-DEVELOPMENT-2018-05-10-a-ubuntu16.04.tar.gz) | May 10, 2018 |
| [Ubuntu 14.04](https://storage.googleapis.com/swift-tensorflow/ubuntu14.04/swift-tensorflow-DEVELOPMENT-2018-05-10-a-ubuntu14.04.tar.gz) | May 10, 2018 |

<details>
  <summary>Older Packages</summary>

### Xcode

| Download |
|----------|
| [May 3, 2018](https://storage.googleapis.com/swift-tensorflow/mac/swift-tensorflow-DEVELOPMENT-2018-05-03-a-osx.pkg) |
| [April 26, 2018](https://storage.googleapis.com/swift-tensorflow/mac/swift-tensorflow-DEVELOPMENT-2018-04-26-a-osx.pkg) |

### Ubuntu 16.04

| Download |
|----------|
| [May 3, 2018](https://storage.googleapis.com/swift-tensorflow/ubuntu16.04/swift-tensorflow-DEVELOPMENT-2018-05-03-a-ubuntu16.04.tar.gz) |
| [April 26, 2018](https://storage.googleapis.com/swift-tensorflow/ubuntu16.04/swift-tensorflow-DEVELOPMENT-2018-04-26-a-ubuntu16.04.tar.gz) |

### Ubuntu 14.04

| Download |
|----------|
| [May 3, 2018](https://storage.googleapis.com/swift-tensorflow/ubuntu14.04/swift-tensorflow-DEVELOPMENT-2018-05-03-a-ubuntu14.04.tar.gz) |
| [April 26, 2018](https://storage.googleapis.com/swift-tensorflow/ubuntu14.04/swift-tensorflow-DEVELOPMENT-2018-04-26-a-ubuntu14.04.tar.gz) |

</details>
<br/>

**Note:** Currently, the Xcode toolchains above only support macOS development. iOS/tvOS/watchOS are not supported.

# Using Downloads

## macOS

### Requirements

* macOS 10.12.4 or later
* Xcode 9.0 beta or later

### 打开Mac的终端输入下面的命令
    brew install vapor/tap/vapor
    
如果没有安装Homebrew，请先安装，这是连接https://brew.sh 

继续输入命令新建一个vapor文件夹

    mkdir ~/vapor
    cd ~/vapor

然后输入下面的命令创建项目
    
    vapor new CPApp --api --branch=beta

接着构建和运行你的项目

    
    cd CPApp
    vapor build
    vapor run
    
  
在浏览器键入. http://localhost:8080/hello 看看是不是返回了“Hello，world！”
如果返回，则代表构建运行成功。

## swift Package Mananfer

接着进行打包，用Xcode打开
继续在终端输入

    vapor xcode -y
   
## 把服务器部署到云端
 如果没有vapor cloud的账户，那就去https://dashboard.vapor.cloud注册一个
 然后继续在终端操作
    
    vapor cloud login //这个登陆你的vaporcloud
    vapor cloud deploy //vapor cloud 部署
 接着在GitHub创建自己的仓库托管
 当终端出现
    GIthub origin url
    >
 在>的后面输入SSH链接
 
    
  
   






