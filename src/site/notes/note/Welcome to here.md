---
{"dg-publish":true,"permalink":"/note/welcome-to-here/","tags":["gardenEntry"]}
---

# [my-odg](https://my-odg.vercel.app/) 🌱

## Recently updated notes
---
| File                                                               | 创建时间             | 修改时间             |
| ------------------------------------------------------------------ | ---------------- | ---------------- |
| [[note/Week 2 软体机器人\|Week 2 软体机器人]]                             | 2025.03.03 13:00 | 2025.03.03 13:05 |
| [[note/1. 刚体驱动和软体驱动的差异\|1. 刚体驱动和软体驱动的差异]]                       | 2025.03.03 13:04 | 2025.03.03 13:05 |
| [[note/Week 1 软体机器人\|Week 1 软体机器人]]                             | 2025.03.02 19:44 | 2025.03.03 13:02 |
| [[note/软体机器人在材料和制造技术方面的最新进展和面临的挑战\|软体机器人在材料和制造技术方面的最新进展和面临的挑战]] | 2025.03.02 20:50 | 2025.03.02 20:53 |
| [[note/论文的两部分\|论文的两部分]]                                         | 2025.03.02 20:46 | 2025.03.02 20:47 |

{ .block-language-dataview}
| File                                                                                          | time              |
| --------------------------------------------------------------------------------------------- | ----------------- |
| [[note/1. 刚体驱动和软体驱动的差异\|1. 刚体驱动和软体驱动的差异]]                                                  | 2025-03-03 13:05  |
| [[note/Week 2 软体机器人\|Week 2 软体机器人]]                                                        | 2025-03-03 13:01  |
| [[note/软体机器人在材料和制造技术方面的最新进展和面临的挑战\|软体机器人在材料和制造技术方面的最新进展和面临的挑战]]                            | 2025-03-02 20:50  |
| [[note/论文的两部分\|论文的两部分]]                                                                    | 2025-03-02 20:46  |
| [[note/Week 1 软体机器人\|Week 1 软体机器人]]                                                        | 2025-03-02 19:45  |
| [[entertainment/cherry studio css\|cherry studio css]]                                     | 2025-02-11 12:55  |
| [[entertainment/shantou travel\|shantou travel]]                                           | 2025-02-04 00:06  |
| [[note/odg.vercel.app推送的文章不能中文开头做标题\|odg.vercel.app推送的文章不能中文开头做标题]]                        | 2025-01-31 10:13  |
| [[entertainment/yunnan travel\|yunnan travel]]                                             | 2025-01-30 23:19  |
| [[entertainment/how about 150 yuan for a day‘s food\|how about 150 yuan for a day‘s food]] | 2025-01-30 23:18  |
| [[note/obsidian操作\|obsidian操作]]                                                            | 2025-01-27 16:53  |
| [[templater/note\|note]]                                                                   | {{date}} {{time}} |
| [[network clipping/clipping try\|clipping try]]                                            | \-                |
| [[note/加工精度和粗糙度讲解 \|加工精度和粗糙度讲解 ]]                                                          | \-                |
| [[note/Welcome to here\|Welcome to here]]                                                  | \-                |

{ .block-language-dataview}

实现代码：
```
table some-tags as "标签" , relevant-tags as "相关标签" , link as "链接" , dateformat(file.ctime, "yyyy.MM.dd HH:mm") as "创建时间" , dateformat(file.mtime, "yyyy.MM.dd HH:mm") as "修改时间"
from ""
where dg-publish = true and inhome = true
sort file.mtime desc
limit 5
```
