### 与浏览器的交互

### 输出
``` 
    // 在网页中输出内容
    document.write();
```
### alert
``` 
    // 警告
    alert('字符串或变量');
```
### confirm(str);
```
    // 确认
    var str = '在消息对话框中要显示的文本';
    confirm(str); 
    // 返回值
    当用户点击"确定"按钮时，返回true
    当用户点击"取消"按钮时，返回false
```
 
### prompt(str1, str2); 
```
    // 提问
    // 参数说明
    str1: 要显示在消息对话框中的文本，不可修改
    str2：文本框中的内容，可以修改
    // 返回值
    1. 点击确定按钮，文本框中的内容将作为函数返回值
    2. 点击取消按钮，将返回null
```

### window.open([URL], [窗口名称], [参数字符串])

 ```
 URL：可选参数，在窗口中要显示网页的网址或路径。如果省略这个参数，或者它的值是空字符串，那么窗口就不显示任何文档。
 窗口名称：可选参数，被打开窗口的名称。
     1.该名称由字母、数字和下划线字符组成。
     2."_top"、"_blank"、"_self"具有特殊意义的名称。
        _blank：在新窗口显示目标网页
        _self：在当前窗口显示目标网页
        _top：框架网页中在上部窗口中显示目标网页
     3.相同 name 的窗口只能创建一个，要想创建多个窗口则 name 不能相同。
    4.name 不能包含有空格。
 参数字符串：可选参数，设置窗口参数，各参数用逗号隔开。
```
参数表:  
<img src="./windowOpenParam.jpg" width="500"/>
