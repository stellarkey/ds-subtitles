# 数据结构MOOC开源字幕组维护计划

2013年夏，学堂在线首批推出7门课程，其中包含《数据结构（上）》。

光阴如梭，数据结构课程推陈出新，其内容和体例都发生了变化。

2021年秋，基于同步教学内容的考量，邓俊辉老师对学堂在线数据结构MOOC的视频章节进行了大量更新。

遗憾的是，很多教学视频还没有匹配字幕（中 + 英）。为了进一步提高课程质量，课程组决定在开源社区发起字幕维护项目。

欢迎大家参与！

# 参与方式

通过 [Pull Request](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) 的方式参与。

- 认领字幕维护任务，在 `README.md`（本文件）中的字幕认领表里**更新认领信息**
- 维护字幕，**更新字幕文件**到 `subtitles/` 文件夹
  - 目前仅支持 `.srt` 格式字幕
  - (自愿)在字幕文件头部署名，格式为：

```
1
00:00:00,000 --> 00:00:04,001
学堂在线MOOC开源字幕组：署名
```

```
1
00:00:00,000 --> 00:00:03,000
XuetangX MOOC OSSG: Your Name
```

## 前备知识/技术

- Github 基本操作
  - [Getting started with GitHub](https://docs.github.com/en/get-started)
- SRT 字幕文件格式
  - [SRT字幕格式](https://www.cnblogs.com/tocy/p/subtitle-format-srt.html)
- (选) Subtitle Edit 开源字幕软件，或同类字幕编辑软件
  - [Subtitle Edit](https://nikse.dk/SubtitleEdit/)（[Learning Videos](https://nikse.dk/SubtitleEdit/Video)）

# 字幕认领表

| 数据结构MOOC视频编号                   | 中文字幕 | 英文字幕 |
| :------------------------------------- | -------- | -------- |
| (Demo) 01E3-1. Max2：递归 + 分治 | @含光    | @含光    |
| 01E2-3. 大师定理/主定理/Master Theorem |     |     |
| 01F1-2. Fib()：递推方程                |          |          |
| 01F2-4. LCS：复杂度                    |          |          |
| 01XA1-1. 缓存                          |          |          |
| 01XA1-2. 循环移位                      |          |          |
| 01XA1-3. 蛮力算法                      |          |          |
| 01XA1-4. 最大公约数                    |          |          |
| 01XA1-5. 翻转                          |          |          |
| 01XA1-6. 再论缓存                      |          |          |
| 02G1.结构                              |          |          |
| 02G2.应用                              |          |          |
| 02G3.快速初始化                        |          |          |
| 03A. 循秩访问                          |          |          |
| 03B-3. 从秩到位置                      |          |          |
| 03E1-6. 性能                           |          |          |
| 04A1-1. 栈                             |          |          |
| 04E1-4. 算法                           |          |          |
| 04G1-2. 体验                           |          |          |
| 05G1. 观察                             |          |          |
| 05G2. 迭代算法                         |          |          |
| 05G4. 分析                             |          |          |
| 05G5. 表达式树                         |          |          |
| 05J1-1. 无前缀冲突编码                 |          |          |
| 05J1-2. 编码成本                       |          |          |
| 05J1-3. 频度                           |          |          |
| 05J2-1. 带权编码成本                   |          |          |
| 05J2-2. 编码算法                       |          |          |
| 05J3-1. 构造编码树                     |          |          |
| 05J3-2. 构造编码表                     |          |          |
| 05J3-3. 解码                           |          |          |
| 06F1-1.拓扑排序                        |          |          |
| 06F1-2.算法                            |          |          |
| 06F1-3.实例                            |          |          |
| 06F2-1.算法                            |          |          |
| 06F2-2.实例                            |          |          |
| 07A1-1. BCC                            |          |          |
| 07A1-2. 叶子                           |          |          |
| 07A1-3. 树根                           |          |          |
| 07A1-4. 内部节点                       |          |          |
| 07A2-1. DFS                            |          |          |
| 07A2-2. 后向边                         |          |          |
| 07A2-3. 树边                           |          |          |
| 07A3. 实例                             |          |          |
| 07B-1. BAG                             |          |          |
| 07B-2. ADT                             |          |          |
| 07C1-1. Shortest Path                  |          |          |
| 07C1-2. The Humble Programmer          |          |          |
| 07C1-3. String Computer                |          |          |
| 07C2. Insight                          |          |          |
| 07C3. Algorithm                        |          |          |
| 07C5-1. Implementation                 |          |          |
| 07C5-2. Parent                         |          |          |
| 07D1-1. Minimum Spanning Tree          |          |          |
| 07D1-2. Applications                   |          |          |
| 07D1-3. Degeneracy & Brute-Force       |          |          |
| 07D2-1. Shortest Bridge                |          |          |
| 07D2-2. Algorithm                      |          |          |
| 07D3. Example                          |          |          |
| 07D4-1. Correctness                    |          |          |
| 07D4-2. Priority = Distance            |          |          |
| 07D5. Implementation                   |          |          |
| 08A2-1. 有序性                         |          |          |
| 08B3-3. 删除：双分支                   |          |          |
| 10C4-6. BB-2R                          |          |          |
| 12F3-3. 实现                           |          |          |
| 12F3-4. 实例                           |          |          |
| 13A-3. ADT                             |          |          |
| 13B-1. 问题与需求                      |          |          |
| 13C4-3. 实现                           |          |          |
| 13C6-3. 前车之覆                       |          |          |
| 13D1-4. 以终为始                       |          |          |
| 13D2-2. 特殊情况                       |          |          |
| 13E1-1. 兼顾经验                       |          |          |
| 13F2-1. 数位溢出                       |          |          |
| 13F2-3. 应对冲突                       |          |          |
