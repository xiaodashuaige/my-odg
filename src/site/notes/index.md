---
{"dg-publish":true,"permalink":"/index/","tags":["gardenEntry"]}
---

# [[Welcome\|Welcome]] 🌱

[my-odg](https://my-odg.vercel.app/)
## Recently updated notes
---
| File                                                                                          | 创建时间             | 修改时间             |
| --------------------------------------------------------------------------------------------- | ---------------- | ---------------- |
| [[entertainment/shantou travel\|shantou travel]]                                           | 2025.02.07 22:51 | 2025.02.04 00:06 |
| [[obsidian操作\|obsidian操作]]                                                                 | 2025.02.07 22:51 | 2025.01.31 11:41 |
| [[odg.vercel.app推送的文章不能中文开头做标题\|odg.vercel.app推送的文章不能中文开头做标题]]                             | 2025.02.07 22:51 | 2025.01.31 10:15 |
| [[entertainment/how about 150 yuan for a day‘s food\|how about 150 yuan for a day‘s food]] | 2025.02.07 22:51 | 2025.01.30 23:27 |
| [[entertainment/yunnan travel\|yunnan travel]]                                             | 2025.02.07 22:51 | 2025.01.30 23:27 |

{ .block-language-dataview}
实现代码：
```
table some-tags as "标签" , relevant-tags as "相关标签" , link as "链接" , dateformat(file.ctime, "yyyy.MM.dd HH:mm") as "创建时间" , dateformat(file.mtime, "yyyy.MM.dd HH:mm") as "修改时间"
from ""
where dg-publish = true and inhome = true
sort file.mtime desc
limit 5
```
