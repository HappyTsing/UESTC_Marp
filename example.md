---
marp: true
theme: gaia
paginate: true
---

<style>section{background-image:url("./img/bg.png");background-size:cover;position:absolute;color:black;}h1{font-size:50px;color:#004098;margin-left:60px;margin-top:-50px!important;}h2{font-size:40px;margin-top:35px;}h3{font-size:30px;margin-top:20px;}p{font-size:25px;}table{text-align:center;font-size:32px;}a{font-size:25px;}li{font-size:30px;text-align:left;}img{margin-left:auto;margin-right:auto;display:block;margin:0 auto;width:25cm;}</style>
<style scoped>section{background-image:url("./img/start.png");background-size:cover;}h1{text-align:center;font-size:75px;color:white;margin-left:0px!important;margin-top:0px!important;}</style>

<style scoped>
  section {
    background-image: url("./img/start.png");
    background-size: cover;
  }
  h1 {
    text-align: center;
    font-size: 75px;
    color: white;
    margin-left: 0px !important;
    margin-top: 0px !important;
  }
</style>

<!-- _class: lead gaia -->

# Marp for UESTC slides <!-- 起始页 -->

---

<style scoped>section{background-image:url("./img/content.png");background-size:cover;}h1{font-size:50px;color:white;margin-top:300px!important;margin-left:5px;}ol{margin-top:-360px;margin-left:600px;}li{font-size:50px;font-weight:bold;color:#004098;margin-top:25px;}</style>

# CONTENT <!-- 目录 -->

1. 列表
2. 代码
3. 公式
4. 表格
5. 图
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

分割行使用 `:-`、`:-:` 或`-:` 可以控制字体相对位置，默认居中。下表为 图片 用的关键字。

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

## 默认居中

![bg 50%](img/example_pic.jpg)

<br><br><br><br><br><br><br><br><br><br><br>

> 欢迎大家来玩 [Bloons TD 6](https://store.steampowered.com/app/960090/Bloons_TD_6/)

---

# 图片

## 左右分离：以左为例

![bg left:30% w:350px h:auto](img/example_pic.jpg)

```
![bg left:30% w:350px h:auto](img/example_pic.jpg)
```

该语法的含义是：

- `left:30%` 左边 30%的空间用于显示图片
- `w: 350px h：auto` 图的宽度为 350px，高度默认

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

<style scoped>section{background-image:url("./img/end.png");background-size:cover;}h1{text-align:center;font-size:75px;color:#004098;margin-left:0px!important;margin-top:-20px!important;}</style>
<!-- _class: lead gaia -->

# THANKS <!-- 结束页 -->
