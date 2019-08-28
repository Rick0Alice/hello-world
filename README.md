# hello-world
test
# MarkDown学习

### 一，标题

#+空格+内容   表示标题

一个#最大，一级标题。支持六级标题

Typora快捷键是Ctrl+数字  0是普通段落大小

### 二，子体设置

- **加粗**

  内容左右用两个*号包起来
  **Typora快捷键Ctrl+B**

- **斜体**

  *内容左右用一个*号包起来*

  *Typora快捷键Ctrl+i*

- **斜体加粗**

  内容左右用三个*号包起来

  ***Typora快捷键Ctrl+i***

- **删除线**

  内容左右用两个~号包起来

  Typora快捷键~~Alt+Shift+S~~

- 居中
- 脚注
- 下标，上标

下标 _ 下标



- 表情符号

- [TOC]目录制作

  ### 三，引用，分割线,插入代码公式等

  > 引用内容前+>
  >
  > > 可以嵌套
  > >
  > > > 无限嵌套  还是**Esc+Enter退出引用**

  > Typora快捷键：Ctrl+Shift+Q

------

  三个或以上的- *都可以

------

  `单行代码用反引号（Esc下面那个键）包起来`

  Typora快捷键Ctrl+Shift+`

------

```
  代码块插入：代码中间用三个反引号包起来，且反引号分别独占一行
  Typora快捷键Ctrl+Shift+k
  公式插入：Typora快捷键Ctrl+Shift+M
```

  

  

### 四，列表

- **无序列表**

  -+*都可以

  Typore快捷键Ctrl+Shift+]

- **有序列表**

  数字+.

  1. 一楼
  2. 二楼

 Typore快捷键Ctrl+Shift+[

​    

  Esc+Enter跳出列表

- **列表嵌套**
  - 一级是实心圆
  - 二级是空心圆
    - 三级及以后是黑心方块
      - 等等。

### 五，表格

```
表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容
```

| 表头 | 表头 | 表头 |
| ---- | :--: | ---: |
| 内容 | 内容 | 内容 |
| 内容 | 内容 | 内容 |

Typore快捷键：Ctrl+T

|      |      |      |
| ---- | ---- | ---- |
|      |      |      |
|      |      |      |
|      |      |      |

​          

### 六，图片

```
![图片alt](图片地址 ''图片title'')
```

图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加

Typore可以直接拖进来。

![TIM图片20190522003819](C:\Users\Administrator\Desktop\work\新建文件夹 (2)\TIM图片20190522003819.jpg)

### 七，超链接

```
[超链接名](超链接地址 "超链接title")
```

title可加可不加

```
[百度](http://baidu.com)
```

[百度](http://baidu.com)

Typora快捷键：Ctrl +k

有的不支持markdown语法的链接处理的，用下面html格式写

`<a href="超链接地址" target="_blank">超链接名</a>`

### 八，流程图

```
​```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
```

```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
```
