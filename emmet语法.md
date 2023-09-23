# emmet 语法

` Emmet语法的前身是Zen coding,它使用缩写,来提高HTML/CSS的编写速度,VScode内部已经集成该语法.`

## 快速生成 HTML 结构

### 1.html 基本结构

> ! + tab 或 Enter 键
> 生成 HTML 基本结构

### 2.生成标签

> 直接输入标签名 不加 <>

```html
<!-- div -->
<div></div>
<!-- img -->
<img src="" alt="" />
```

### 3. class 和 id 快速生成

> class 生成 div.class
> id 生成 div#demo

```html
<!-- .demo+#div 或者div.demo+div#div -->
<div class="demo"></div>
<div id="div"></div>
```

### 4. 生成多个标签(\*)

> div\*3

```html
<!-- div.demo*3 -->
<div class="demo"></div>
<div class="demo"></div>
<div class="demo"></div>
```

### 5.子节点（>）和兄弟节点（+）

> div>img
> div+img

```html
<!-- div>span -->
<div><span></span></div>
<!-- div+p -->
<div></div>
<p></p>
```

#### 复合使用 `ul>li#two`

```html
<!-- p.one+div.demo -->
<p class="one"></p>
<div class="demo"></div>
<!-- ul>li#two -->
<ul>
  <li id="two"></li>
</ul>
```

### 6.生成属性（[]）

> a[href = "" target=""]

```html
<!-- a[href="" target=""] -->
<a href="" target=""></a>
```

### 7.自增符号$

```html
<!-- div.demo$*3 -->
<div class="demo1"></div>
<div class="demo2"></div>
<div class="demo3"></div>
```

### 8.标签内部写内容{}

```html
<!-- div{hello}*3 -->
<div>hello</div>
<div>hello</div>
<div>hello</div>
```

### 9.自增序列+自带内容

> div{$}\*5

```html
<!-- div{h$}*5 -->
<div>h1</div>
<div>h2</div>
<div>h3</div>
<div>h4</div>
<div>h5</div>
```

## 快速生成 CSS 样式

> w200 => width : 200px;
>
> h200 => height : 200px;
