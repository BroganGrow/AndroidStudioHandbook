# AndroidStudioPracticalHandbook（Android Studio 开发实用手册 ）

## 前言
```
	从Eclipse转到Android Studio阵营已经好长一段时间了，同时也从一开始的陌生、格格不入，到后来的越发熟练自如地使用整个AS
开发环境（由于篇幅较长,统一用As代替Android Studio）。不得不说，刚开始用AS的时候确实会遇到很多小问题，比如说：不知道如何把
Android项目结构换成project；不知道如何设置项目的字体大小和风格；不知道如何使用As的快捷键（之前Eclipse的快捷键很多都无效了）
等等。总的来说，这些其实都是一些很小的问题，但就是因为一些很小的问题，让你不得不百度找各种解决办法，当然了，百度后肯定是有
答案的，可是呢，你花在其中的时间就会浪费很多了。
	我们是谁？--程序员！！程序员是干啥的？--当然是敲代码了！！所以我们应当以花费最小的时间为目的，把更多的时间用在代码和
优化的问题上。这就是我写这文章的目的，同时也是为了方便自己或其他开发者查阅相关资料。
	注意：本文章是基于最新的Android studio 3.2.0 版本、Windows系统的基础下编写的，Mac OS X也可参考下，不排除因为系统、
快捷键有所差别。
```
## 手册特点
* 作为实用手册，侧重在于实用，有些过于偏僻的功能可能不会介绍到
* 主要解决As工作环境的问题，而非教导如何编程的。
* 追求利用手册更加有效率的解决问题
* 以图文为主，代码为辅
* 同步更新AS新版本的特性
* 不定期更新AS的文章

## 目录
* [第1章 Android Studio 起步](#测试)
  * [系统要求](AndroidStudioPracticalHandbook/Article/第1章-AndroidStudio起步/系统要求.md)
  * [Android Studio 开发环境搭建](AndroidStudioPracticalHandbook/Article/第1章-AndroidStudio起步/AndroidStudio开发环境搭建.md) 
  * 搭建多版本共存的Android Studio
  * 工作区中文提示
  * 创建应用
  * 目录结构

* 偏好设置
  * 界面风格、字体
  * Log显示设置
  * 显示代码行号
  * 设置鼠标悬浮提示
  * 自动导包、删除无用包
  * 文档编码格式
  * 恢复工作区间默认设置
  * 重启AS默认打开内容
  * 类注释
  * 显示缩进空格
  * 默认文件编码格式
  * 关闭/打开，自动检测AS版本更新
  * BookMark工具
  * TODO 提示

* 常用工具
  * 快速定位当前页面在项目中的位置
  * 快速回退、前进
  * .9图片

* 常用快捷键
  * 自定义快捷键
  * 常用快捷键

* 优秀插件
  * GsonFormat 格式化json数据
  * ADBWIFI 真机ADB WiFi调试
  * Sexy Editor 设置工作区的背景
  * AndroidButterKnife 配合ButterKnife框架使用 

* 调试
  * debug 调试
  * 打印 Log

* 项目完整流程
  * 完整项目
  	* 创建项目
  	* 导入项目
  	* 创建library
  	* 导入library
  	* 合并项目
  	* AS 2.x 升级到 3.x
  * 单元测试
  * 混淆
  * 签名
  * 打包
  	* Android App Bundle
  	* 传统apk打包
  	* 多渠道打包
  	* 运行自动签名 （微信登录之类需要）
  * 发布

* VCS版本控制系统
  * Git
  	* 内置
  	* 外置
  * SVN
  	* 内置
  	* 外置

* Gradle

* 常见问题解决
   * 整个项目代码报错（引入红色），但仍可正常运行解决方法
     * Android Studio R文件爆红但是项目可以运行
       https://blog.csdn.net/hx7013/article/details/79971980
       https://blog.csdn.net/losingcarryjie/article/details/79489403

 * 拓展

    * 上传项目到bintrary

### 参考
https://github.com/bxiaopeng/AndroidStudio

## 更新日志
* 2019/1/14:初步完成提纲
* 2019/1/14:初步完成提纲
* 2019/1/14:初步完成提纲