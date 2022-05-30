# $$makedown的一个应用$$ #
_markdown是一种GitHub支持的语法在标准markdown语法的基础上做了修改，称为Github Flavored Markdown，简称GFM_
# 1. 快捷一级二级标题 #
　　一行下面写=，上行字体最大
=
　　一行下面写-，上行字条次大
-

# 2. 显示横线 #

---

# 3. 补空行 #
不想上下两个不同的布局方式交错到一起的时候，就要在两种布局之间补一个空行.

# 4. #的作用是标题的级别 #
># 一级标题<br>
>>## 二级标题<br>
>>>### 三级标题<br>
>>>>#### 四级标题<br>
>>>>>##### 五级标题<br>
>>>>>>###### 六级标题

# 5. 换行 #
你<br>
好<br>
啊

# 6. 邮箱和邮箱悬停文字 #
[网易邮箱](http://www.126.com)<br>
[网易邮箱](http://www.126.com "我的邮箱1950482839@qq.com")<br>

# 7. 行首空格被忽略，可以输入两个全角空格 #
　　大家好


# 8. 表示高亮 #
我是`中国人`<br>

# 9. 圆点和多级圆点 #
* 编程语言
    * 脚本语言
        * Python

# 10. 缩进 #
>数据结构
>>树
>>>二叉树
>>>>平衡二叉树
>>>>>满二叉树

# 11. 插入图片 图片出错是会有字显示 #
![一个图片的实例](https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fup.enterdesk.com%2Fedpic_source%2F53%2Fb9%2F7b%2F53b97bfd3ae56da2712c03bd8ff22b3b.jpg&refer=http%3A%2F%2Fup.enterdesk.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=auto?sec=1655451526&t=1d5a631038b40fa0e70d2c1c0b4a8411) <br>

# 12. 鼠标悬停图片时 显示提示信息 #
![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")<br>

# 13. 给图片加上超链接 #
[![baidu](http://www.baidu.com/img/bdlogo.gif "百度Logo")](http://baidu.com)<br>

# 14. 插入片段 无语法高亮功能 #
```
你好，世界!!!
```

# 15. 插入代码片段,实现语法高亮 #
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
# 16. 未完待续................................................. #
