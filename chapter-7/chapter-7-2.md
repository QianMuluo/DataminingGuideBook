## 训练阶段

首先，我们统计所有文本中一共出现了多少个不同的单词，记作“|Vocabulary|”（总词汇表）。对于每个单词w<sub>k</sub>，我们将计算P(w<sub>k</sub>|h<sub>i</sub>)，每个h<sub>i</sub>（喜欢和讨厌两种）的计算步骤如下：

1. 将该分类下的所有文章合并到一起；
2. 统计每个单词出现的数量，记为n；
3. 对于总词汇表中的单词w<sub>k</sub>，统计他们在本类文章中出现的次数n<sub>k</sub>：
4. 最后应用下方的公式：

![](../img/chapter-7/chapter-7-10.png)
