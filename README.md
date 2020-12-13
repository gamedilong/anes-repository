# anes-repository
## 插件源码地址  
* https://github.com/gamedilong/anes
## rom 仓库

* 该仓库是小霸王插件的，远程资源仓库，内容主要在list.json中维护，文档持续完善中。
* 有其他问题意见也可以加qq群 858843908 沟通交流
* 插件地址 https://marketplace.visualstudio.com/items?itemName=gamedilong.anes

## 资源更新 
* 如果有想要添加得资源，可以在群里反馈，也可以fork分支PR上来，测试通过后会尽快发布
* 修改方式，在list.json中添加配置即可
示例
```
[
...
{
    "name":"坦克大战",
    "url":"http://11.down.thenightblindness.com:8000/fc/Battle.City(J).zip",
    "fileName":"Battle.City(J).zip",
    "nesName":"Battle City (J).nes"
}
...
]
name remote中展示名称
url 资源下载链接
fileName  与url最后得资源名称保持一致
nesName  该压缩文件解压后的nes内容完整名称 (压缩文件名，与文件名不一定一致)
```

## FAQ
* **下载一直在99%**   该问题已经升级了一个0.02的版本有遇到的同学可以更新下插件，另外最好删除一下C盘用户文件夹下的.anes文件重新打开即可。新的第三方如果没有挂掉的话，应该是可以正常下载了。
* **兼容性问题** 目前支持vscode版本 1.47.0+
* **remote列表不显示** 原因可能是github的资源列表没用下载成功，可以删掉(C:\Users\XXXX\.anes)目录，然后关闭vscode重新打开会重新下载。如果依然没有，可直接下载  https://github.com/gamedilong/anes-repository/archive/master.zip  将内容解压的C:\Users\XXXX\.anes\remote下
 最终目录结构如下 C:\Users\XXX\.anes\remote\anes-repository-master  
 注 : mac目录 为 /User/XXX/.anes
* **本地rom打开黑屏问题** 使用的jsnes模拟器，部分rom不支持。后续如果找到好的mapper适配方案，会优先适配issue里反馈的比较多的rom。 
