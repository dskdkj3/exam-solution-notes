---
title: "2023-06 高等数学一（II）期末真题"
display_title: "2023-06 高等数学一（II）期末真题"
course: "高等数学一（II）"
exam_month: "2023-06"
source_note: "原始 PDF 未随仓库发布；题目文本由扫描 PDF OCR、整理并经人工复核。考试月份按下学期期末时间推定为 2023-06。"
run_slug: "23-gaoshu1-ii-final"
stage: "markdown_draft"
status: "draft"
kind: "source_correction_log"
---

# 2023-06 高等数学一（II）期末真题来源纠错记录

> 状态：draft。本文记录来源解析中的笔误、错解、排版错误或其它会影响答案可信度的问题。普通 OCR 不确定性不要写入这里，除非已经复核原图并确认是来源材料自身的问题。

## q003-c001

> 状态：confirmed；类别：source_wrong_answer；题号：3；source_pages: [2]；reviewer: user

### 来源原文

来源解析末行把傅里叶级数的和函数写为
\[
\begin{cases}
x, & x\ne 2n\pi,\\
\dfrac{\pi^2}{2}, & x=2n\pi,
\end{cases}
\quad n\in\mathbb Z.
\]

用户已复核原图：分段式第一行确为 $x$，不是 OCR 把 $x^2$ 误读成 $x$。

### 本版修正

本版答案采用
\[
S(x)=
\begin{cases}
(x-2k\pi)^2, & 2k\pi<x<2(k+1)\pi,\ k\in\mathbb Z,\\
2\pi^2, & x=2k\pi,\ k\in\mathbb Z.
\end{cases}
\]

### 依据

题干给定 $f(x)=x^2,\ x\in[0,2\pi)$，并以 $2\pi$ 为周期。来源解析前文计算出的傅里叶系数也对应这个周期延拓。按傅里叶和函数定理，连续点处和函数应等于周期延拓后的函数值；在 $x=2k\pi$ 处取左右极限平均：
\[
\frac{0+(2\pi)^2}{2}=2\pi^2.
\]

因此来源解析末行的 $x$ 与 $\pi^2/2$ 均不采纳，视为来源解析疑似原始错误。

### 对外说明

本版纠正了来源解析第 3 题傅里叶级数和函数的末行错误：原解析把周期延拓的平方函数写成了一次函数，并给出错误跳点值；本版按题干、系数推导和傅里叶和函数定理给出修正。
