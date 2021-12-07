\!\[\]\[logo\]

\[\!\[api\]\[apiSvg\]\]\[api\]
\[\!\[License\]\[licenseSvg\]\]\[license\]

## 中文 \| [English](/README_EN.md)

## 建议

推荐使用[Chrome]浏览器或[Firefox]浏览器阅读，其他浏览器可能不支持目录跳转，影响阅读。

## 前言

由来：回想起以前一路摸索AS的坎坷还有如今时而碰到的一些关于AS的问题，都需要花不少的时间查阅相关资料，于是便突发奇想，为何不自己整理出一本关于AS的手册呢。

从Eclipse转到AndroidStudio阵营已经好长一段时间了，同时也从一开始的陌生、格格不入，到后来的越发熟练自如地使用整个AS开发环境（由于篇幅较长,统一用As代替AndroidStudio)。不得不说，刚开始用AS的时候确实会遇到很多小问题，比如说：不知道如何把Android项目结构换成project；不知道如何设置项目的字体大小和风格；不知道如何使用As的快捷键（之前Eclipse的快捷键很多都无效了）等等。总的来说，这些其实都是一些很小的问题，但就是因为一些很小的问题，让你不得不百度找各种解决办法，当然了，百度后肯定是有答案的，可是呢，你花在其中的时间就会浪费很多了。

所以我们应当以花费最小的时间为目的，把更多的时间用在代码和优化的问题上。这就是我写这文章的目的，同时也是为了方便自己或其他开发者查阅相关资料。

注意：本文章是基于最新的Android studio 3.2.0 版本(截止到2019/01/14，)、Windows系统的基础下编写的，Mac OS X也可参考下，不排除因为系统、快捷键有所差别。由于AS的功能过于强大，不少偏僻的功能可能不会用到，所以我们这里主要还是以实用的为主。

## 针对人群

* 新手：快速入门
* 老手：可重新系统学习一遍

## 手册特点

* 作为实用手册，侧重在于实用，有些过于偏僻的功能可能不会介绍到
* 主要解决As工作环境的问题，而非教导如何编程的。
* 追求利用手册更加有效率的解决问题
* 以图文为主，代码为辅
* 同步更新AS新版本的特性
* 不定期更新AS的文章

## 目录

* [第1章 Android Studio 起步](/Article/%E7%AC%AC1%E7%AB%A0-AndroidStudio%E8%B5%B7%E6%AD%A5/README.md)
* [第2章 Settings偏好设置](/Article/%E7%AC%AC2%E7%AB%A0-Settings%E5%81%8F%E5%A5%BD%E8%AE%BE%E7%BD%AE/README.md)
* [第3章 File文件](/Article/%E7%AC%AC3%E7%AB%A0-File%E6%96%87%E4%BB%B6/README.md)
* [第4章 Edit编辑](/Article/%E7%AC%AC4%E7%AB%A0-Edit%E7%BC%96%E8%BE%91/README.md)
* [第5章 View视图](/Article/%E7%AC%AC5%E7%AB%A0-View%E8%A7%86%E5%9B%BE/README.md)
* [第6章 Navigate导航](/Article/%E7%AC%AC6%E7%AB%A0-Navigate%E5%AF%BC%E8%88%AA/README.md)
* [第7章 Code代码](/Article/%E7%AC%AC7%E7%AB%A0-Code%E4%BB%A3%E7%A0%81/README.md)
* [第8章 Analyze分析](/Article/%E7%AC%AC8%E7%AB%A0-Analyze%E5%88%86%E6%9E%90/README.md)
* [第9章 Refactor重构](/Article/%E7%AC%AC9%E7%AB%A0-Refactor%E9%87%8D%E6%9E%84/README.md)
* [第10章 Build构建](/Article/%E7%AC%AC10%E7%AB%A0-Build%E6%9E%84%E5%BB%BA/README.md)
* [第11章 Run运行](/Article/%E7%AC%AC11%E7%AB%A0-Run%E8%BF%90%E8%A1%8C/README.md)
* [第12章 Tools工具](/Article/%E7%AC%AC12%E7%AB%A0-Tools%E5%B7%A5%E5%85%B7/README.md)
* [第13章 VCS版本控制](/Article/%E7%AC%AC13%E7%AB%A0-VCS%E7%89%88%E6%9C%AC%E6%8E%A7%E5%88%B6/README.md)
* [第14章 Window窗口](/Article/%E7%AC%AC14%E7%AB%A0-Window%E7%AA%97%E5%8F%A3/README.md)
* [第15章 Help帮助](/Article/%E7%AC%AC15%E7%AB%A0-Help%E5%B8%AE%E5%8A%A9/README.md)
* [第16章 Bulid构建错误汇集](/Article/%E7%AC%AC16%E7%AB%A0-Bulid%E6%9E%84%E5%BB%BA%E9%94%99%E8%AF%AF%E6%B1%87%E9%9B%86/README.md)
* [第17章 AndroidStudio版本](/Article/%E7%AC%AC17%E7%AB%A0-AndroidStudio%E7%89%88%E6%9C%AC/README.md)
* [第18章 其它](/Article/%E7%AC%AC18%E7%AB%A0-%E5%85%B6%E5%AE%83/README.md)

#### 由于个人的精力有限，某些部分可能会出错，可在[issues]提出！

## 参考资料

https://github.com/bxiaopeng/AndroidStudio
https://developer.android.google.cn/studio

## 更新日志

[ChangeLog](/ChangLog.md)

## 许可证

```
Copyright 2019 Brainbg

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

\[logo\]: https://raw\.githubusercontent\.com/Brainbg/CloudPic/master/AndroidStudioHandbook/chapter1/%20finallogo\.png

\[Chrome\]:https://www\.google\.cn/intl/zh\-CN/chrome/

\[Firefox\]:http://www\.firefox\.com\.cn/

\[licenseSvg\]: https://img\.shields\.io/badge/License\-Apache\-\-2\.0\-brightgreen\.svg
\[license\]: https://github\.com/Brainbg/AndroidStudioHandbook/blob/master/LICENSE

\[apiSvg\]: https://img\.shields\.io/badge/API\-19%2B\-brightgreen\.svg
\[api\]: https://android\-arsenal\.com/api?level=19

\[issues\]: https://github\.com/Brainbg/AndroidStudioHandbook/issues