---
{"dg-publish":true,"permalink":"/note/welcome-to-here/","tags":["gardenEntry"]}
---

# [my-odg](https://my-odg.vercel.app/) 🌱

## Recently updated notes
---
| File                                                                                                                             | 创建时间             | 修改时间             |
| -------------------------------------------------------------------------------------------------------------------------------- | ---------------- | ---------------- |
| [[note/homework4\|homework4]]                                                                                                 | 2025.04.16 14:16 | 2025.04.16 15:45 |
| [[note/homework3\|homework3]]                                                                                                 | 2025.03.27 19:01 | 2025.03.27 19:52 |
| [[note/homework2\|homework2]]                                                                                                 | 2025.03.26 14:58 | 2025.03.26 15:30 |
| [[note/homework1\|homework1]]                                                                                                 | 2025.03.19 14:24 | 2025.03.20 18:11 |
| [[note/A Discussion on Machining Precision and Surface Roughness\|A Discussion on Machining Precision and Surface Roughness]] | 2025.02.26 13:39 | 2025.03.03 13:21 |

{ .block-language-dataview}
| File                                                                                                                                                         | time              |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------- |
| [[note/homework4\|homework4]]                                                                                                                             | 2025-04-16 14:17  |
| [[note/homework3\|homework3]]                                                                                                                             | 2025-03-27 19:01  |
| [[note/homework2\|homework2]]                                                                                                                             | 2025-03-26 14:58  |
| [[note/homework1\|homework1]]                                                                                                                             | 2025-03-19 15:11  |
| [[note/A Discussion on Machining Precision and Surface Roughness\|A Discussion on Machining Precision and Surface Roughness]]                             | 2025-03-03 13:21  |
| [[note/Advancements and Challenges in Robotics for Materials and Manufacturing\|Advancements and Challenges in Robotics for Materials and Manufacturing]] | 2025-03-03 13:16  |
| [[note/two point in the paper\|two point in the paper]]                                                                                                   | 2025-03-03 13:15  |
| [[note/Differences between rigid body and soft body driving\|Differences between rigid body and soft body driving]]                                       | 2025-03-03 13:05  |
| [[note/Week 2 软体机器人\|Week 2 软体机器人]]                                                                                                                       | 2025-03-03 13:01  |
| [[note/Week 1 软体机器人\|Week 1 软体机器人]]                                                                                                                       | 2025-03-02 19:45  |
| [[entertainment/cherry studio css\|cherry studio css]]                                                                                                    | 2025-02-11 12:55  |
| [[entertainment/shantou travel\|shantou travel]]                                                                                                          | 2025-02-04 00:06  |
| [[note/odg.vercel.app推送的文章不能中文开头做标题\|odg.vercel.app推送的文章不能中文开头做标题]]                                                                                       | 2025-01-31 10:13  |
| [[entertainment/yunnan travel\|yunnan travel]]                                                                                                            | 2025-01-30 23:19  |
| [[entertainment/how about 150 yuan for a day‘s food\|how about 150 yuan for a day‘s food]]                                                                | 2025-01-30 23:18  |
| [[note/obsidian操作\|obsidian操作]]                                                                                                                           | 2025-01-27 16:53  |
| [[templater/note\|note]]                                                                                                                                  | {{date}} {{time}} |
| [[attachment/未命名 2025-03-28 18.58.49.excalidraw\|未命名 2025-03-28 18.58.49.excalidraw]]                                                                     | \-                |
| [[network clipping/clipping try\|clipping try]]                                                                                                           | \-                |
| [[note/Untitled\|Untitled]]                                                                                                                               | \-                |
| [[note/Welcome to here\|Welcome to here]]                                                                                                                 | \-                |
| [[note/软体机器人传感器应用分析\|软体机器人传感器应用分析]]                                                                                                                       | \-                |
| [[note/未命名\|未命名]]                                                                                                                                         | \-                |

{ .block-language-dataview}

实现代码：
```
table some-tags as "标签" , relevant-tags as "相关标签" , link as "链接" , dateformat(file.ctime, "yyyy.MM.dd HH:mm") as "创建时间" , dateformat(file.mtime, "yyyy.MM.dd HH:mm") as "修改时间"
from ""
where dg-publish = true and inhome = true
sort file.mtime desc
limit 5
```
