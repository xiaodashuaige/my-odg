---
{"dg-publish":true,"permalink":"/note/welcome-to-here/","tags":["gardenEntry"]}
---

# [my-odg](https://my-odg.vercel.app/) 🌱

## Recently updated notes
---
| File                     | 创建时间             | 修改时间             |
| ------------------------ | ---------------- | ---------------- |
| [[note/First\|First]] | 2025.09.17 18:50 | 2025.09.17 18:53 |

{ .block-language-dataview}
| File                                               | time              |
| -------------------------------------------------- | ----------------- |
| [[note/First\|First]]                           | 2025-09-17 18:51  |
| [[templater/note\|note]]                        | {{date}} {{time}} |
| [[note/Welcome to here\|Welcome to here]]       | \-                |
| [[network clipping/clipping try\|clipping try]] | \-                |

{ .block-language-dataview}

实现代码：
```
table some-tags as "标签" , relevant-tags as "相关标签" , link as "链接" , dateformat(file.ctime, "yyyy.MM.dd HH:mm") as "创建时间" , dateformat(file.mtime, "yyyy.MM.dd HH:mm") as "修改时间"
from ""
where dg-publish = true and inhome = true
sort file.mtime desc
limit 5
```
