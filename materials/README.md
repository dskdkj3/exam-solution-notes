# Materials

这里按课程存放公开材料。

## 已发布材料

- [2025-06 高等数学一（II）期末真题（B卷）](gaoshu1-ii/2025-06-final/)
- [2024-06 高等数学一（II）期末真题](gaoshu1-ii/2024-06-final/)

## 目录结构

建议结构：

```text
materials/
  <course-slug>/
    <yyyy-mm-exam-slug>/
      README.md
      01-仅题目.md
      02-多解法参考答案.md
      03-详解.md
      04-拓展讲解.md
      05-A-B卷差异.md   # 可选：来源存在 A/B 卷或变体时
      06-纠错清单.md
      manifest.json
```

示例：

```text
materials/
  gaoshu1-ii/
    2025-06-final/
    2024-06-final/
```

单套材料的 `README.md` 要直接告诉读者：

- 这是什么考试或练习；
- 哪个文件适合先看；
- PDF 下载链接在哪里；
- 是否有已知纠错或版本说明。
