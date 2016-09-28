# MarkdownBasic

#这是一个<font color="green">Markdown</font>语法练习
##二级菜单
###三级菜单
####四级菜单
正文
列表  

AT&T
*斜体*  
两个空格+回车键才是换行  
**加粗**  
\*_{}[]#+-.!都要号要加转义符\
<font color="red">红色</font>  
1.  有序列表Bird(要空2格才能成为列表)
2.  有序列表McHale
3.  有序列表Parish

*  无序列表1(要空2格才能成为列表)
*  无序列表2
*  无序列表2  
*  
*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
    viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
    Suspendisse id sem consectetuer libero luctus adipiscing.

*   This is a list item with two paragraphs<font color="skeyblue">(**多行内容**)</font>.

    This is the second paragraph in the list item. You're
    only required to indent the first line. Lorem ipsum dolor
    sit amet, consectetuer adipiscing elit.

*   Another item in the same list.
+  无序列表+  
-  无序列表-  


---
***
> 这是一个引用  
>>这是二级引用  
>>空4格或者tab表示代码段，没有颜色区分 
  
    var a=new Object();  
    console.log(a.__proto__);  
    console.log(a.__proto__.constructor);   
    
>>用\`\`\`+语言名+<代码段>+\`\`\`来表示代码段，有颜色区分  
```JavaScript  
var a=new Object();   
console.log(a.__proto__);  
console.log(a.__proto__.constructor);   
```  

<font face="微软雅黑" color="#BA4245" size="6">文字链接</font>   

*inline方式*  `[新浪](http://www.sina.com.cn)  `  
[新浪](http://www.sina.com.cn)  
*Refrence方式*  `[网易][netEase_url]`  
`[netEase_url]:http//www.netease.com`  
[网易][netEase_url]  
[netEase_url]:http//www.netease.com
<font face="微软雅黑" color="#BA4245" size="6">图片链接</font>  
<font face="微软雅黑" color="blue" size="4">**inline方式：**</font>  
`![](http://www.ikea.com/ms/zh_CN/img/2015_img/homepage/hpfu_how/Services2.jpg)`  
![](http://www.ikea.com/ms/zh_CN/img/2015_img/homepage/hpfu_how/Services2.jpg)  
<font face="微软雅黑" color="blue" size="4">**Refrence方式：**</font>  
`![][r1_url]
[r1_url]:http://www.ikea.com/ms/img/header/logo.gif `

![][r1_url]
[r1_url]:http://www.ikea.com/ms/img/header/logo.gif  
<font face="微软雅黑" color="#BA4245" size="4">地址带有括号的图片链接</font>  
<font face="微软雅黑" color="blue" size="4">**inline方式：**</font>  
`![](http://latex.codecogs.com/gif.latex?\prod(n_{i})+1)  `

![](http://latex.codecogs.com/gif.latex?\prod(n_{i})+1)  
<font face="微软雅黑" color="blue" size="4">**Refrence方式(较好)：**</font>  
`![][1]
[1]:http://latex.codecogs.com/gif.latex?\prod(n_{i})+1  `  

![][1]
[1]:http://latex.codecogs.com/gif.latex?\prod(n_{i})+1  
