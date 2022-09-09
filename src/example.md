---
marp: true
theme: uestc
# 显示页码，首页不显示
paginate: true
_paginate: false
math: katex
---

<style scoped>
  h1 {
    font-size: 75px;
    color: white;
    margin: 0 !important;
  }
</style>
<!--
_class: lead
_backgroundImage: url("../img/start.png"),url("https://happytsing-figure-bed.oss-cn-hangzhou.aliyuncs.com/uestc_marp/start.png")
_backgroundSize: cover
 -->

# Marp for UESTC slides <!-- 起始页 -->

---

<style scoped>
  h1 {
    font-size: 50px;
    color: white;
    margin-top: 300px !important;
    margin-left: 5px;
  }
  ol {
    margin-top: -360px;
    margin-left: 600px;
  }
  li {
    font-size: 50px;
    font-weight: bold;
    color: #004098;
    margin-top: 25px;
  }
</style>

<!--
_backgroundImage: url("../img/content.png"),url("https://happytsing-figure-bed.oss-cn-hangzhou.aliyuncs.com/uestc_marp/content.png")
_backgroundSize: cover
-->

# CONTENT <!-- 目录 -->

1. 列表
2. 代码
3. 公式
4. 表格
5. 图片
6. 其他语法

---

# 列表

## 有序列表

1. 有序列表 1
2. 有序列表 2

## 无序列表

- 无序列表 1
- 无序列表 2

---

# 代码

## 行内代码

`System.out.println("Hello, World!"）`

## 块状代码：

```java
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

---

# 公式

## 行内公式

$\sum_{i=1}^{N}{x_i}$

## 块状公式：

$$

D(x) = \begin{cases}
\lim\limits_{x \to 0} \frac{a^x}{b+c}, & x<3 \\
\pi, & x=3 \\
\int_a^{3b}x_{ij}+e^2 \mathrm{d}x,& x>3 \\
\end{cases}


$$

---

# 表格

分割行使用 `:-`、`:-:` 或`-:` 可以控制字体相对位置，默认居中。下表为图片用到的关键字。

| 关键字  | 说明                             |
| ------- | -------------------------------- |
| cover   | 缩放大小填充整页幻灯片 (Default) |
| contain | 缩放大小适应整页幻灯片           |
| fit     | contain 别名, 兼容 Deckset.      |
| auto    | 使用原始大小                     |
| x%      | 指定缩放百分比                   |

示例：`![bg cover](path/to/image.png)`

> 注意：此处必须是 bg！而不是通常情况下的任意图片名

---

# 图片

## 图片大小

```markdown
![width:200px](image.jpg) <!-- 设置宽度为 200px -->
![height:30cm](image.jpg) <!-- 设置高度为 300px -->
![width:200px height:30cm](image.jpg) <!-- 设置宽高 -->
![w:32 h:32](image.jpg) <!-- 支持缩写，设置大小为 32x32 px -->
```

## 图片滤镜

常用的如下，其余参见[图片过滤](https://caizhiyuan.gitee.io/categories/skills/20200730-marp.html#图片过滤)

```markdown
![blur:10px]() <!-- 马赛克模糊 -->
![sepia:1.0]() <!-- 黑白图 -->
![opacity:.5]() <!-- 白色滤镜 -->
```

---

# 图片

## 默认居中

![bg 50%](../img/example_pic.jpg)

<br><br><br><br><br><br><br><br><br><br><br>

> 欢迎大家来玩 [Bloons TD 6](https://store.steampowered.com/app/960090/Bloons_TD_6/)

---

# 图片

## 左右分离：以右为例

![bg right:30% w:350px h:auto](../img/example_pic.jpg)

```
![bg right:30% w:350px h:auto](../img/example_pic.jpg)
```

该语法的含义是：

- `right:30%` 右侧 30% 的空间用于显示图片
- `w: 350px h：auto` 图的宽度为 350px，高度默认

> 备注：尽量不要将图片放在左边，这将导致 H1 的位置错误

---

# 图片

## horizontal

存在两种布局格式，默认为横向的 horizontal 布局。

```markdown
![bg right:60% w:350px h:auto](../img/example_pic.jpg)
![bg w:350px h:auto](../img/example_pic.jpg)
```

此时 `right:60%` 意思是两张图片共同占据右侧 60%的空间

![bg right:60% w:350px h:auto](../img/example_pic.jpg)
![bg w:350px h:auto](../img/example_pic.jpg)

---

# 图片

## vertical

通过为**第一张图**添加关键字，修改为纵向的 vertical 布局。

```markdown
![bg vertical right:40% w:400px h:auto](../img/example_pic.jpg)
![bg  w:400px h:auto](../img/example_pic.jpg)
```

![bg vertical right:40% w:400px h:auto](../img/example_pic.jpg)
![bg  w:400px h:auto](../img/example_pic.jpg)

---

# 其他语法

## 链接

[Marpit](https://marpit.marp.app/)

## 字体

**粗体**
_斜体_
~~删除~~
<br> 强制换行

## 引用

> Marpit theme for UESTC, generate fancy PPT based on Markdown conveniently

---

<style scoped>
  h1 {
    font-size: 75px;
    margin-left: 0px !important;
    margin-top: -20px !important;
  }
</style>

<!--
_backgroundImage: url("../img/end.png"),url("https://happytsing-figure-bed.oss-cn-hangzhou.aliyuncs.com/uestc_marp/end.png")
_backgroundSize: cover
_class: lead
-->

# THANKS <!-- 结束页 -->
