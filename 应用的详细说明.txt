markdown是一种GitHub支持的语法在标准markdown语法的基础上做了修改，称为Github Flavored Markdown，简称GFM。<br>
1 整行字体<br>

一行下面写=，上行字体最大<br>
=
一行下面写-，上行字条次大<br>
-
2 显示横线<br>
-，=上方无文字，显示成横线。但-要至少三次<br>

---
3 补空行：不想上下两个不同的布局方式交错到一起的时候，就要在两种布局之间补一个空行。<br>
4 前面用#,个数增加，字体变小。最多6个#<br>
# 一级标题<br>
## 二级标题<br>
### 三级标题<br>
#### 四级标题<br>
##### 五级标题<br>
###### 六级标题
5 换行用<>里面写上br<br>
6 链接可直接写<br>
如果要显示文字，则显示文字用[]括住，链接用()括住。例如：<br>
[网易邮箱](http://www.126.com)<br>
则链接文字为网易邮箱，点击它可以跳转到http://www.126.com<br>
可以用双引号给悬停显示文字，例如：<br>
[网易邮箱](http://www.126.com "我的邮箱1950482839@qq.com")<br>
　　7 行首空格被忽略，可以输入两个全角空格<br>
8 表示高亮用`括住`<br>
>* 9 行首，*后加一个空格，显示圆点(表达列表时用)<br>
>>* 二级圆点，三级圆点，是最前面加一个和两个TAB<br>
* 编程语言
    * 脚本语言
        * Python

10 缩进，用>。例如：<br>
>数据结构
>>树
>>>二叉树
>>>>平衡二叉树
>>>>>满二叉树

11 插入图片<br>
\!\[出错信息\]\(图片网址\)
![一个图片的实例](https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fup.enterdesk.com%2Fedpic_source%2F53%2Fb9%2F7b%2F53b97bfd3ae56da2712c03bd8ff22b3b.jpg&refer=http%3A%2F%2Fup.enterdesk.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=auto?sec=1655451526&t=1d5a631038b40fa0e70d2c1c0b4a8411) <br>
[]里面的字符串，在无法显示图片时显示，可以不要()里面是图片的链接。也就是说，文件中插入的图片，是放在网上的。<br>
如果是github仓库中的图片，图片地址为：https://github.com/ 你的用户名 / 你的项目名 / raw / 分支名 / 存放图片的文件夹 / 该文件夹下的图片 把raw换成blob也可以鼠标指向图片文件，右击，点“复制链接”,这样也可以得到图片的链接。<br>
12 如果你想达到 鼠标悬停 显示提示信息，那么可以仿照前面介绍的文本中的方法，就是这样：<br>
```cpp
![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")
```
在URL后面，加一个双引号包围的字符串，显示效果如图：<br> 
![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")<br>

13 给图片加上超链接<br>
如果你想使图片带有超链接的功能，即点击一个图片进入一个指定的网页。那么可以这样写：<br>
```
[![baidu](http://www.baidu.com/img/bdlogo.gif "百度Logo")](http://baidu.com)
```
[![baidu](http://www.baidu.com/img/bdlogo.gif "百度Logo")](http://baidu.com)<br>
14 插入代码片段<br>
我们需要在代码的上一行和下一行用` `` 标记。\```不是三个单引号，而是数字1左边，Tab键上面的键。要实现语法高亮那么只要在\``` 之后加上你的编程语言即可（忽略大小写）。c++语言可以写成c++也可以是cpp。看代码：<br>
\```Java<br>
public static void main(String[]args){}//Java<br>
\```<br>
\```c<br>
int main(int argc, char *argv[])//c<br>
\```<br>
\```Bash<br>
echo "hello GitHub"#Bash<br>
\```<br>
\```javascript<br>
document.getElementById("myH1").innerHTML="Welcome to my Homepage";//javascipt<br>
\```<br>
\```cpp<br>
string &operator+(const string& A,const string B)//cpp<br>
\```<br>

```Java
public static void main(String[]args){}//Java
```
```c
int main(int argc, char *argv[])//c
```
```Bash
echo "hello GitHub"#Bash
```
```javascript
document.getElementById("myH1").innerHTML="Welcome to my Homepage";//javascipt
```
```cpp
string &operator+(const string& A,const string B)//cpp
```

