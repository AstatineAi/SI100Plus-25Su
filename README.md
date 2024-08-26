# SI 100+ Summer 2024

## 课件

### 线上课件

[Lecture 0: 环境配置](https://teafrogsf.github.io/SI100Plus/Lecture_00_Environment/)

[Lecture 1: 编程语言和 Python 简介](https://teafrogsf.github.io/SI100Plus/Lecture_01_Python_Intro/)

[Lecture 2: 变量、运算符、表达式](https://teafrogsf.github.io/SI100Plus/Lecture_02_Var_Operator_Expr/)

[Lecture 3: 函数](https://teafrogsf.github.io/SI100Plus/Lecture_03_Function/)

[Lecture 4: 控制流](https://teafrogsf.github.io/SI100Plus/Lecture_04_Control_Flow/)

去掉链接末尾可能出现的 `/#/` 部分，加上 `?print-pdf`，然后使用浏览器的打印功能，可以将网页保存为 PDF 文件。

### 线下预览

```bash
git clone https://github.com/teafrogsf/SI100Plus.git
cd SI100Plus
npm install -g reveal-md
reveal-md Lecture_01_Python_Intro/Lecture_01_Python_Intro.md -w
# 更改上面的路径即可预览其他课件
```

打开命令行中提示的链接，即可在浏览器中预览课件。

## 教学计划

### Python 课程内容大纲

- 第一部分：编程语言和Python简介
  1. 课程概览
  2. 基本知识扫盲、编程语言简史（机器码 -> 汇编 -> 高级语言）、Python简介
  3. 编程工具简介：VSCode（编辑器），Python 解释器概念辨析，程序在“哪里”运行
  4. 最小示例: Hello, World（交互式、脚本式）
  5. 用自然语言语法类比编程语言语法，在 REPL 用赋值、==、is 等简单语句演示
- 第二部分：变量、运算符、表达式
  1. Python 基本语法（关键字,缩进,注释）
  2. 字面值与赋值语句、变量与基本数据类型
  3. 浮点数与误差
  4. 运算符与优先级、标准/文件输入输出
  5. 最小示例：A + B Problem
  6. 布尔类型、比较运算符、布尔运算
  7. 逻辑表达式
- 第三部分：函数
  1. `help()`与代码提示的使用，内置函数初探，ipython `?` 查询功能
  2. 函数与方法
  3. 最小示例：数学函数，字符串操作
  4. 定义函数、调用函数
  5. 参数传递、默认参数、返回值、作用域
  6. 传入函数的函数(High order function)
  7. 最小示例：比大小，斐波那契数列
- 第四部分：控制流（Control Flow）：条件判断和循环
  1. `if` `if-else` `if-elif-else` Nested-`if` 语句、布尔转换
  2. 最小示例：编写判断函数
  3. `while` 循环、死循环、`break` 与 `continue`
  4. 最小示例：进制转换
  5. `List` 列表类型、列表操作、元组与列表
  6. `for` 循环、`for ... in`
  7. 最小示例：循环构造列表
  8. 列表推导式 - list comprehension
  9. 依照 Step 数简单分析代码性能瓶颈（时间复杂度初步）
- 第五部分：Python 进阶
  1. 常用数据类型：List, Dict, Tuple, etc. 和相关操作
  2. 常用高级语法：解包、多变量赋值、行内 `if-else`、lambda 表达式
  3. 打印调试法，使用IDE调试代码，养成良好的代码习惯
  4. `import`，标准库，第三方库，pip & PyPI，如何找到 & 正确阅读所使用库的文档，`conda` 与虚拟环境

