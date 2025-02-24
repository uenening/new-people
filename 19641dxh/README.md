### [着迷的主页]（https://github.com/270809520)

## Markdown学习经历：

&ensp;首先是打算去mooc上学学的，可是貌似没有，也可能是我没找到，然后就通过百度，哔哩哔哩了解了下markdown是什么
<br>
&ensp;其次通过不断了解和学习诼渐有了一定的认识
<br>
&ensp;最后通过和同学的学习与学长的交流，不断尝试才有了下面的成果
<br>
&ensp;虽然在这个过程中还是遇到了不少问题，但我也是乐在其中



# Markdown的学习内容，实践，成果

## 一、标题
在想要设置为标题的文字前面加#来表示
一个`#`是一级标题，二个`#`是二级标题，以此类推。支持六级标题。
注：标准语法一般在#后跟个空格再写文字，貌似简书不加空格也行。
<br>
列;<br>
`#` 这是一级标题<br>
`##` 这是二级标题<br>
`###` 这是三级标题<br>
`####` 这是四级标题<br>
`#####` 这是五级标题<br>
`######` 这是六级标题<br>
效果如下;
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题
## 二、文字
### 1.加粗
要加粗的文字左右分别用两个*号包起来
### 2.斜体
要倾斜的文字左右分别用一个*号包起来
### 3.斜体加粗
要倾斜和加粗的文字左右分别用三个*号包起来
### 4.删除线
要加删除线的文字左右分别用两个~~号包起来

效果如下；
<br>
**这是加粗的文字**
*这是倾斜的文字*`
***这是斜体加粗的文字***
~~这是加删除线的文字~~
<br>
## 三、引用
在引用的文字前加>即可。引用也可以嵌套，如加两个>>三个>>>
n个...
貌似可以一直加下去，但没实际意义<br>
示例：
<br>
>这是引用的内容
>>这是引用的内容
>>>>>>>>>>这是引用的内容

## 四、分割线
三个或者三个以上的 - 或者 * 都可以。
`---`
`----`
`***`
`*****`

效果如下;
<br>
---
----
***
*****

## 五、图片
### 1.![图片alt](图片地址 ''图片title'')

图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加<br>
如下:
```
![blockchain](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/
u=702257389,1274025419&fm=27&gp=0.jpg "区块链")
```
### 六、超链接
### 1.`[超链接名]`(超链接地址 "超链接title")
title可加可不加<br>
如下;
```
[Github](https://github.com/)
[百度](http://baidu.com)
```
效果;
[Github](https://github.com/)
[百度](http://baidu.com)
## 七、列表
### 1.无序列表
无序列表用 - + * 任何一种都可以
```
- 列表内容
+ 列表内容
* 列表内容
```
效果如下;

- 列表内容
+ 列表内容
* 列表内容<br>
注意：- + * 跟内容之间都要有一个空格
### 2.有序列表
数字加点
列如;
```
1.列表内容
2.列表内容
3.列表内容
```
如下
1.列表内容<br>
2.列表内容<br>
3.列表内容<br>
注意：序号跟内容之间要有空格

### 3.列表嵌套
上一级和下一级之间敲三个空格即可

## 八表格

表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

如下;
<br>
```
表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容
```
第二行分割表头和内容。
- 有一个就行，为了对齐，多加了几个
文字默认居左
-两边加：表示文字居中
-右边加：表示文字居右
注：原生的语法两边都要用 | 包起来。不过在这里我把它省略掉了
列；<br>
```
姓名|技能|排行
--|:--:|--:
dxh|唱|老大
dxh|跳|老二
dxh|rap|老三

```
姓名|技能|排行
--|:--:|--:
dxh|唱|老大
dxh|跳|老二
dxh|rap|老三
## 九代码

### 1.单行代码：代码之间分别用一个反引号包起来
效果如下:
`代码内容`
     `we are dxh;`
### 2.代码块：代码之间分别用三个反引号包起来，且两边的反引号单独占一行
效果如下:
  ```
  代码...
  代码...
  代码...
  ```
```
    function fun(){
         echo "dxh会唱跳rap";
    }
    fun();
```
## 十流程图
```
flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
```
## 十一.其他
### 生成目录 在文档中增加” [TOC]”（[TOC]需独占一行才能发挥）可以自动给文档生成目录

### 空间 
`&emsp;` 全角空间
`&ensp;` 半角空间
`&nbsp; `半角的不断行的空白格（推荐使用）

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>


# Java环境配置历程：
## 1.下载JDK
## 2.配置环境变量
## 3.JAVA_HOME 设置
## 4.PATH设置
## 5.CLASSPATH 设置
## 6.测试JDK是否安装成功
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>




  # 虚拟机的安装历程：
  ## 1.解压好学长发的VMware Workstation Pro
  ## 2.点击创建虚拟机，下一步
  ## 3.选择自己想要的操作系统，我选的是linxu(注意要选iox的话需要另寻途径)
  ## 4.取好名称
  ## 5.选择磁盘大小
  ## 6.安装位置，点击完成
  （注：由于没有对应的映像文件，安装的这种虚拟机为临时的)
  
 


































