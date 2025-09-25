# 预览

[TOC]

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题

## 段落

**粗体**

*斜体*

***粗斜体***

~~删除线~~

高亮：==可是说真话的愿望有多么强烈，受到的各种干扰就有多么大。我悲哀的发现，根本就无法还原真实==，记忆总是被我的情感改头换面，并随之捉弄我，背叛我，把我搞的头脑混乱，真伪难辨。

## 引用

> **《数到十》**
>
> 爱上一个人两颗心三分想念
>
> 四刷过五月天倒数跨年
>
> 当爱碎成了白雪六出纷飞
>
> 错过一个人两颗心单身三年
>
> 七月的第八天分手纪念
>
> 那时的我们说了九次再见十分怀念

> [!note]
>
> 强调用户在快速浏览文档时也不应忽略的重要信息。

> [!TIP]
>
> 有助于用户更顺利达成目标的建议性信息。

> [!important]
>
> 对用户达成目标至关重要的信息。

> [!Warning]
>
> 因为可能存在风险，所以需要用户立即关注的关键内容。

> [!caution]
>
> 行为可能带来的负面影响。

## 代码

代码：`code` 

代码块

```jsx
import { useState } from 'react';

// 行内注释
export default function App() {
  const [count, setCount] = useState(0);
  
  const increment = () => {
    setCount(count + 1);
  }
  
  return (
    <button onClick={increment}>
      Clicked {count} times
    </button>
  );
}
```

## 列表

### 有序列表

1. 列表项1
2. 列表项2
   1. 嵌套列表项1
   2. 嵌套列表项2
      1. 嵌套列表项3
      2. 嵌套列表项4

### 无序列表

- 列表项1
- 列表项2

  - 嵌套列表项1

  - 嵌套列表项2
    - 嵌套列表项3
    - 嵌套列表项4

### Task List

- [x] 未完成

- [ ] 已完成

## 链接

### 超链接

[Github](www.github.com)

### 图片链接

![Acg](https://fastly.jsdelivr.net/gh/YasakaKanoko/charlotte@main/post/1752917116.webp)

## 表格

| name   | value | Example |
| :----- | ----- | ------- |
| auto   | 1     |         |
| none   | 2     |         |
| kimi   | 3     |         |
| hajimi | 4     |         |
|        |       |         |

## 公式

行内公式：文本中的变量 $x = 5$ 和函数 $f(x) = x^2 + 2x + 1$。

块级公式：$$f(x) = ax^2 + bx + c$$

## 脚注


鲁迅[^1]

[^1]: 鲁迅，原名周树人

<kbd>Ctrl</kbd>+<kbd>F</kbd>
