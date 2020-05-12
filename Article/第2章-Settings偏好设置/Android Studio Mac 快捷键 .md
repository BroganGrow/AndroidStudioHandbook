# Android Studio Mac 快捷键<!-- omit in toc --> 

- [1.File 文件](#1file-文件)
- [2.Edit 编辑](#2edit-编辑)
  - [2.1 Find 查找](#21-find-查找)
- [3.View 视图](#3view-视图)
- [4.Navigate 导航](#4navigate-导航)
- [5.Code 代码](#5code-代码)
- [6.Analyze 分析](#6analyze-分析)
- [7.Refactor](#7refactor)
- [8.Build 构建](#8build-构建)
- [9.Run 运行](#9run-运行)
- [10.tools 工具](#10tools-工具)
- [代码编辑](#代码编辑)
- [注释](#注释)
- [切换](#切换)
- [代码重构](#代码重构)
- [快捷指令](#快捷指令)
- [参考](#参考)

Command  Shift  Control 

## 1.File 文件
- Command + , : Preferences 偏好设置
- Command + ; : Project Structure 项目结构
- Command + S : 保存


## 2.Edit 编辑
- Command + Z : Undo 撤销
- Command + Shift + Z : Redo 恢复撤销
- Command + X : Cut 剪切
- Command + C : Copy 复制           
- Command + Shift + C : Copy Paths 复制文件路径        
- Command + Shift + Option + C : Copy Reference 复制引用      
- Command + V : Paste 粘贴         
- **Command + Shift + V : Paste from History 粘贴历史，从粘贴板上选择**       
- Command + Shift + Option + V : Paste without Formatting 无格式粘贴   
- Command + Shift + 8 :Column Selection Mode
- Command + A : Select All 选择所有
- Option + ↑ : Extend Selection 
- Option + ↓ : Shrink Selection 
- Command  + Shift + return : Complete Current Stattement
- Control + Shift + J :Join Lines
- Command + D : Duplicate Line or Selection  复制行或者代码块
- Tab ：Indent Selection 缩进
- Shift +Tab : Unindent Line or Selection 取消缩进
- **Command + Shift + U : Toggle Case 字母大小写转换**
- Command + Control + Space : Emoji & Symbols 表情和符号
### 2.1 Find 查找
- Command + F：Find 当前页面查找
- Command + R：Replace 当前页面替换
- Command + Shift + F :Find in Path 全局查找
- Command + Shift + R :Replace in Path 全局替换
- Command + G : Find Next 
- Command + Control + G : Select All Occurrences
- Control + G : Add Selection for Next Occurrence
- Control + Shift + G : Unselect Occurrence 
- Control + Option + ↓ :Go to next highlighted element usage
- Control + Option + ↑ :Go to previous highlighted element usage
- Option + F7 : Find Usages 
- Command + Option + Shift + F7 : Find Usages Settings
- Command + Option + F7 : Show Usages
- Command + F7 : Find Usages in File
- Command + Shift+ F7 : Highlight Usages in File
- 
## 3.View 视图
- Command + 1 : Project 项目 
- Command + 2 : Favorites 收藏夹
- Command + 3 : Find 查找
- Command + 4 : Run 运行
- Command + 6 : Logcat 日志
- Command + 7 : Structure 结构
- Command + 9 : Version Control 版本控制
- Command + E : Recent Files 显示最近打开过的文件
- Option + Shift + C :最近修改
- **Command + P: Parameter Info 列出函数方法所支持的参数列表**
- Control + Shift + P : Type Info
- Control + Shift + Q : Context Info
- Command + Shift + E : Recent Locations 最近的位置
- Control + ` : Quick Switch Scheme 快速切换方案
- Command + Control + F : Enter Full Screen 进入/退出全屏模式

## 4.Navigate 导航
## 5.Code 代码
## 6.Analyze 分析
## 7.Refactor
## 8.Build 构建
## 9.Run 运行
## 10.tools 工具



## 代码编辑

- F1 / Control + J : Quick Documentation 快捷查看文档
- Command + D ：复制当前行
- Command + Delete :删除当前行
- 双Shift ：全局搜索任意内容

- Command + O :全局搜索类
- Command + Option + O :全局搜索类/方法/参数
- 双Command + E :显示最近打开并修改过的文件
- Command + 鼠标点击：跳转到相关来源
- Command + U :跳转至超类的方法
- Command + L :跳转至第几行，快速定位
- Command + Shift + Delete :跳转至上次改动过的地方

- Fn+ F2:跳转至错误或警告的位置
- Fn+ F1:查看类/方法的注释文档


- **Command + N /Control+ Return：快速生成Getter/Setter方法、构造犯法、toString方法**
- **Command + Shift +Return : 自动补全细节**
- **Option +Return : 自动补全细节**
- Control + O :引入重写父类的方法
- Control + I :引入接口或者抽象类方法的实现
- Command + Shift + V : 选择使用剪切板内容
- Control + Shift + J : 合并行，去空格
- Control + Option + I: 自动对齐
- **Control + Option + O: 清除无效包引用**
- Command + ,:打开设置
- **Command + -/+ :折叠/展开代码块**
- **Command + Shift +  -/+ :折叠/展开全部代码块**
- Command + W : 关闭当前编辑窗口
- Option + F7 : 查看被引用的地方

- **Command + Shift + ↑/↓:代码块上下整体移动,只能在方法内移动**
- **Option + Shift + ↑/↓:代码块上下整体移动,可以移出方法内**
- **Command + Option + L:代码格式化**
- **Command + Option + T :生成结构体 （if/else/try/catch等）**
- Control + Option + H :查找调用的位置
- **Control + R : 运行**
- **Control + D : 调试**
- **Option + Return :快速修复**



## 注释
- Command + /: 注释 （//）
- Command + Option + /: 注释 （/**/）
- /** + 回车 ：详细注释


## 切换

- Control + Tab :切换文件或工具


## 代码重构
- Command + Option + M :方法重构分离
- Command + Option + P :参数重构，将方法内变量抽离成方法参数
- Command + Option + V :抽离为局部变量
- Command + Option + F :抽离为成员变量
- Command + Option + C :把局部变量修改成static final的全局变量
- Shift + F6: 类名、方法名、变量名 重命名操作


## 快捷指令
- **Command + J ：快速生成模板代码块**
- psf 生成 public static  final 
- prsf 生成 private static  final 
- psfi 生成 public static final int  
- psfs 生成 public static final String 
- const 生成 private static final int  : 定义常量
- fixme 生成 // FIXME: 2020-03-15 ：待修复点
- foreach 生成 for (:) { } ：foreach模板
```java
     for (:
             ) {
            
        }
```
- fori
```java
  for (int i = 0; i < ; i++) {
            
        }
```
- geti 生成 public static S getInstance() { return ; } ：插入单例方法
- key 生成 private static final String KEY_ = "" :生成key
- logt 生成 private static final String TAG = "S";:当前类的TAG
- main 或者 psvm  生成 public static void main(String[] args) { } ：main方法
- newInstance
- noInstance 生成  private S() {/*no instance*/} 
- noop 生成   /* no-op */
- todo 生成  // TODO: 2020-03-15 /:待办事项
- stopship 生成 // STOPSHIP: 2020-03-15 ：停止事项
- ViewConstructors
```java
    public className(Context context) {
        this(context, null);
    }

    public className(Context context, AttributeSet attrs) {
        this(context, attrs, 0);
    }

    public className(Context context, AttributeSet attrs, int defStyle) {
        super(context, attrs, defStyle);
        
    }
```
- starter 
```java
    public static void start(Context context) {
        Intent starter = new Intent(context, S.class);
        starter.putExtra();
        context.startActivity(starter);
    }
- sbc:块注释的结构代码
```java
///////////////////////////////////////////////////////////////////////////
// 
///////////////////////////////////////////////////////////////////////////
```
- .var
- .try
- .nn
``````java
  if (input != null) {
            
        }
```





## 参考
https://www.jianshu.com/p/b8dffb784069
https://www.cnblogs.com/spring87/p/4720844.html
