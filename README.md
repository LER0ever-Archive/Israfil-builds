# Israfil-builds
Build every commits of [LER0ever/Israfil](https://github.com/LER0ever/Israfil) using CI AutoTag  
本repo利用持续集成自动tag并将编译结果上传至[Releases](https://github.com/LER0ever/Israfil-builds/releases)  
Releases里标签名称为“平台-编译器-版本号-时间戳”， 如macx-clang-0.1.0.0003-115355  
如有Issues请至[LER0ever/Israfil](https://github.com/LER0ever/Israfil)提交  
# Israfil 下载
### [点我到Releases](https://github.com/LER0ever/Israfil-builds/releases)

## 编译状态
| Windows g++ | Linux g++ | OS X Clang |
| :---: | :---: | :---: |
| ![appveyor](https://ci.appveyor.com/api/projects/status/t8ry0hmnriu0ncx1?svg=true)|![travis](https://api.travis-ci.org/LER0ever/Israfil-builds.svg)|![travis](https://api.travis-ci.org/LER0ever/Israfil-builds.svg)|

OSX的自动编译暂停，因为我没有办法通过命令行安装Qt5.7，等待Brew支持5.7的安装。