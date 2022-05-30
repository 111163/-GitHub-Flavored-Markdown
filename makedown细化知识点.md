<a id="top"></a>
# $$makedown细化知识点$$ #
# 1.  标题 #
># 一级标题 #
>>## 二级标题 ##
>>>### 三级标题 ###
>>>>#### 四级标题 ####
>>>>>##### 五级标题 #####
>>>>>>###### 六级标题 ######
# 2. 标题的另一种写法 #
　　一级标题 
=
　　二级标题
-
正文文本
# 3. 表示引用 #
>梦想还是要有的，万一实现了呢。 --马云 <br>
>人没有梦想和咸鱼有什么区别。   --周星驰
# 4. 加粗和倾斜 #
我的目标:*技术高手*<br>
我的爱好:_听歌_,_唱歌_<br>
最喜欢的颜色:**红色**<br>
最喜欢的数字:__9__<br>
人生理想:***世界大同***
# 5. 无序列表 #
* 程序语言列表:
	* C
	* C++
	* Python
+ 数据库列表:
	+ MySQL
	+ Oracle
	+ PostGreSQL
- NoSQL列表:
	- Redis
		- MongoDB
	- HBase
# 6. 有序列表 #
那些年一起学过的语言
1. Pascal
2. C
3. C++
4. Python
5. Java
6. Lua
# 7. 超链接 #
<https://www.baidu.com><br>
[百度](https://www.baidu.com)<br>
[搜狗](https://www.sogou.com)
# 8. 表格 #
| 国内IT巨头 | 国际IT巨头 |
| ---------- | ---------- |
| 阿里巴巴 | 苹果 |
| 腾讯 | 微软 |
| 百度 | 谷歌 |
# 9. 图片 #
![赵灵儿](https://imgsa.baidu.com/forum/w%3D580/sign=d6981fe03b87e9504217f3642039531b/7336970a304e251ff552f4dba686c9177f3e5369.jpg)
# 10. 代码段 #
```
#include <stdio.h>
int main(int argc, char* argv[], char* envp[])
{
	printf("Hello world!!!");
	return 0;
}
```
# 11. 兼容html语法-貌似没什么用 #
<span style="color:red;font-size:30px">
梦想，需要努力去实现
</span><br>

# 12. 转义 #
不使用转义时:<br>
# 
使用转义时:<br>
\#
# 13. 删除线 #
~~这是一错误的文本~~
# 14. 锚点连接 #
[回到文章开头](#top)
# 15. 开头输入空格 #
　前面有一个空格
# 16. 语法高亮代码段 #
```cpp
#include <iostream>
using namespace std;
int main(int argc, char* argv[], char* envp[])
{
	cout << "Hello world!!!"<<endl;//this is a cpp
	return 0;
}

```
# 17. 树形结构 #
>数据结构
>>树
>>>二叉树
>>>平衡二叉树
>>>>满二叉树
# 18. 凸显词高亮 #
我是`好人`
# 19. 补空行表示格式分离 #
# 20. LaTex公式 #
$x^n+y^n=z^n$
$$x^n+y^n=z^n$$
$$x=\dfrac{-b\pm\sqrt{b^2-4ac}}{2a}$$
$x=\dfrac{-b\pm\sqrt{b^2-4ac}}{2a}$
# 21. 注脚 #
这是一个注脚$^1$的样例。<br>
这是第二个注脚$^2$的样例。<br>
[^1]: 这是一个*注脚*的**文本**。<br>
[^2]: 这是另一个*注脚*的**文本**。<br>
# 22. # 
