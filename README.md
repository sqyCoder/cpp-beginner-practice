# 入门编程 55 题

> 学 C++ 的第一批代码。**55 个文件，全部是入门阶段的练习**：循环、条件、数组、函数、基础数学题。
>
> 这个仓库不太「好看」——文件名是拼音缩写，有几道题甚至忘了改名。但它完整记录了一个人从「不知道 for 怎么写」到「能用数组和函数解题」的那段路，所以留着。

<p>
  <img alt="C++" src="https://img.shields.io/badge/C%2B%2B-55-00599C?style=flat-square&logo=cplusplus&logoColor=white">
  <img alt="难度" src="https://img.shields.io/badge/难度-入门-52C41A?style=flat-square">
</p>

---

## 为什么文件名是拼音

因为写这些代码的时候还没养成命名习惯。`runnian.cpp` 是闰年，`shuixianhua.cpp` 是水仙花数，`jitutl.cpp` 是鸡兔同笼。

这也是这个仓库最有意思的地方：**它是一份「未整理过的真实学习记录」**。没有重构、没有统一命名、没有补注释——就是当时写出来的样子。翻回去看，能清楚看到哪些习惯是后来才学会的（比如「把功能相同的代码抽成函数」这件事，前 20 个文件里一次都没出现）。

---

## 内容索引

### 循环与条件（最基础的一批）

| 文件 | 题目 |
| --- | --- |
| [1-7day.cpp](1-7day.cpp) | 七天循环 |
| [while1-10.cpp](while1-10.cpp) | while 循环 1~10 |
| [printf1-1003.cpp](printf1-1003.cpp) | 打印 1~100 |
| [99.cpp](99.cpp) | 九九乘法表 / 99 问题 |
| [compare.cpp](compare.cpp) | 大小比较 |
| [er.cpp](er.cpp) | 偶数判断 |
| [runnian.cpp](runnian.cpp) | 闰年判断 |
| [xuanz.cpp](xuanz.cpp) | 选择结构 |

### 数组与字符串

| 文件 | 题目 |
| --- | --- |
| [shuzhu.cpp](shuzhu.cpp) | 数组基本操作 |
| [sjleixdaxiao.cpp](sjleixdaxiao.cpp) | 数组大小 / 数组类型 |
| [sjianzhuan.cpp](sjianzhuan.cpp) | 数组旋转 |
| [nixu.cpp](nixu.cpp) | 逆序输出 |
| [daoxu.cpp](daoxu.cpp) | 倒序 |
| [paixu.cpp](paixu.cpp) | 排序 |
| [max.cpp](max.cpp) | 求最大值 |
| [duijiaoxian.cpp](duijiaoxian.cpp) | 对角线打印（二维数组） |
| [star.cpp](star.cpp) | 星型图案 |
| [sjx.cpp](sjx.cpp) | 三角形图案 |

### 数字处理

| 文件 | 题目 |
| --- | --- |
| [fdusn.cpp](fdusn.cpp) | 分解数字 |
| [geiweuhe'.cpp](geiweuhe'.cpp) | 各位求和 |
| [szjh.cpp](szjh.cpp) | 数字求和 |
| [weishujishuang.cpp](weishujishuang.cpp) | 位数统计 |
| [zhenshu.cpp](zhenshu.cpp) | 整数处理 |
| [zhenshudegewei.cpp](zhenshudegewei.cpp) | 整数的个位 |
| [zhengsdeshiwei.cpp](zhengsdeshiwei.cpp) | 整数的十位 |
| [dychufa.cpp](dychufa.cpp) | 带余除法 |
| [yysj.cpp](yysj.cpp) | 余数计算 |
| [jis.cpp](jis.cpp) | 计数 |

### 数学题

| 文件 | 题目 |
| --- | --- |
| [a+b.cpp](a+b.cpp) | 两数求和 |
| [fbnq.cpp](fbnq.cpp) | 斐波那契数列 |
| [fenshuqiuhe.cpp](fenshuqiuhe.cpp) | 分数求和 |
| [gyueshu.cpp](gyueshu.cpp) | 最大公约数 |
| [zfsjx.cpp](zfsjx.cpp) | 辗转相减 |
| [sushu.cpp](sushu.cpp) | 素数判断 |
| [zshu.cpp](zshu.cpp) | 质数 |
| [shuixianhua.cpp](shuixianhua.cpp) | 水仙花数 |
| [wansu2.cpp](wansu2.cpp) | 完全数 |
| [huangqian.cpp](huangqian.cpp) | 黄金分割 |
| [yiyuan.cpp](yiyuan.cpp) | 一元二次方程 |
| [neijiaohe.cpp](neijiaohe.cpp) | 内角和 |
| [tianshu.cpp](tianshu.cpp) | 天数计算 |
| [jitutl.cpp](jitutl.cpp) | 鸡兔同笼 |
| [monkey.cpp](monkey.cpp) | 猴子问题 |
| [jaimi.cpp](jaimi.cpp) | 加密 |
| [aiplane.cpp](aiplane.cpp) | 飞机问题 |

### 函数与递归

| 文件 | 题目 |
| --- | --- |
| [wuca.cpp](wuca.cpp) | 无参函数 |
| [jdt.cpp](jdt.cpp) | 阶乘 |
| [jishaung1.cpp](jishaung1.cpp) | 阶乘（第二种写法） |
| [hlwd.cpp](hlwd.cpp) | 汉罗塔 |
| [guess.cpp](guess.cpp) | 猜数字 |

### 早期遗留（未改名）

| 文件 | 说明 |
| --- | --- |
| [3.cpp](3.cpp) | 第 3 题，忘了改名字 |
| [9.cpp](9.cpp) | 第 9 题，同上 |
| [dayzfu.cpp](dayzfu.cpp) | 拼音缩写含义已不可考，代码本身可跑 |

> 这几个文件就是「当时应该改名但没改」的证据。留着比删掉诚实。

---

## 怎么跑

```bash
g++ -O2 -std=c++17 a+b.cpp -o a && ./a
```

这些题都是**标准输入输出**，跑起来手动喂数据即可。

---

## 回头看，哪些东西是后来才学会的

如果要用这个仓库做反面教材，这几点最有价值：

1. **命名**。拼音缩写省了 5 秒，代价是三个月后自己也看不懂。**文件名应该说明「这是什么」，不是「这念什么」**。
2. **抽函数**。前 20 个文件里，同一段「读入 → 计算 → 输出」被复制了 20 次。学会抽函数之后，代码量少了一半。
3. **注释**。这个仓库几乎没注释。当时觉得「代码这么短不需要」，现在觉得「正因为短才需要——因为你会忘记它为什么这么写」。
4. **边界条件**。早期的代码基本没考虑「输入是 0 怎么办」「除数是 0 怎么办」。这是从「能跑」到「可靠」之间唯一的一道坎。

---

## 这个仓库的意义

它不是简历项目，也不会有人 star。

但它是一个坐标：**从这里开始，到能写出 [tuoyixia](https://github.com/sqyCoder/tuoyixia)、[slow-1e8](https://github.com/sqyCoder/slow-1e8) 那样的东西，中间大概是两年。**

留着它，是因为每个人的第一个 `for` 循环都值得被记住。

---

## License

个人学习存档，代码可自由参考。
