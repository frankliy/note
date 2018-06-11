---
在最上方输入‘---’+空格，即可产生YAML FONT Matters
---

## Typora笔记

### 生成目录

​	输入‘ [toc]+换行键 ’

### 代码块

1. 开头	```+语言名

   输入```javascript,输出JavaScript代码块。

``` javascript
var a = "This is a javascript"；
var b = a;
a = "赋值与引用"；
alert(b);//This is a javascript
```

2. 用``在段落中表示代码

   ``` javascript
   " This is `init()` function "
   ```

    输出如下：

   This is `init()` function

### 列表

1. 无序列表

   开头*/+/-,空格+文字，Enter键换行，双击Enter键跳出。

   - 轻解罗裳
   - 独上兰舟
   - 红藕香残玉簟秋

2. 有序列表

   开头数字+.+空格+文字，Enter键换行，双击Enter键跳出。（二级列表：清除前面序号，开头数字+.+空格+文字，连按三次Enter键跳出并返回一级列表）

   1. 雁字回时，月满西楼。
   2. 一种相思，两处闲愁。
   3. 才下眉头，却上心头。

3. 可选列表

   开头*/+/- +空格+[+空格+]+空格+文字，Enter键换行，双击Enter键跳出。

   * [ ] 云中谁寄锦书来
   * [x] 花自飘零水自流
   * [ ] 此情无计可消除

### 表格

开头|+列名+|+列名+|+列名|+Enter键，创建一个3*2表格，鼠标点击表格弹出编辑尺寸，行/列数，字体对齐。

| 姓名   | 年龄 | 性别 |
| ------ | ---- | ---- |
| 一剪梅 | 18   | **   |

### 插入图片

格式如下：

```html
![Alt text](path/to/img.jpg)
```

![]()

### 插入链接

1. 超链接

   用[]括住超链接的内容，紧接着用()括住超链接

   > 点击+[+百度+]+(+https://www.baidu.com/+"百度"+)搜索

   点击[百度](https://www.baidu.com"百度")搜索

2. URLS

   用<>括住url

   > <+www.baidu.com+>

   <www.baidu.com/>

3. 内链接 相关链

   使用[+超链接文字+]+[+标签+]，创建可定义链接

   ```
   1.[百度][1]
   2.[baidu][]
   3.[1]:https://www.baidu.com
   4.[baidu]:https://www.baidu.com
   ```

   [百度](https://www.baidu.com/)

   [baidu](https://www.baidu.com/)

### 引用

> 开头>+空格，这是一段引用。

### 脚注

这是一个脚注+[+^+1+]+

这是一个脚注[^1]

### 快捷键

1. 标题：Ctrl+数字
2. 代码块：开头```+语言名（html）
3. 无序列表：*+空格+文字
4. 有序列表：数字+.+空格+文字
5. 表格：Ctrl+T
6. 插入图片：Ctrl+shift+i
7. 插入链接：Ctrl+k
8. 选中一整行：Ctrl+L
9. 选中单词：Ctrl+D
10. 选中相同格式的文字：Ctrl+E
11. 查找：Ctrl+F
12. 替换：Ctrl+H
13. 加粗：Ctrl+B
14. 斜体：Ctrl+i
15. 下划线：Ctrl+u
16. 删除线：Alt+shift+5
17. 跳转文章开头：Ctrl+Home
18. 跳转文章结尾：Ctrl+End
19. 可选序列：*+空格+[+空格+]+文字
20. 水平线：***+换行键
21. 引用：>+空格+文字







[TOC]