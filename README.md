# 100-pandas-puzzles-cn

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VXenomac/100-pandas-puzzles-cn/blob/master/)

本 Repo 是 100-pandas-puzzles 的中文版，目前将要开始翻译清理数据部分，英文原版请移步[这里](https://github.com/ajcr/100-pandas-puzzles)。

受 [numpy-100](https://github.com/rougier/numpy-100) 的启发，本仓库将提供 100 个（仍在更新）小问题用于测试你对 Pandas 的掌握。

Pandas 是一个具有非常多专业特性和功能的大型库，由于时间和能力所限，本仓库并不能全面涉及。本仓库设计的练习主要集中在利用 DataFrame 和 Series 对象操作数据的基础上（索引、分组、聚合、清洗）。许多问题的解决方案只需要几行代码，因此选择正确的方法和遵循最佳实践是基本目标。

练习题将根据难度等级来划分，当然，这些等级是主观的，但也这些等级也可以作为难度的大致参考，让你对题目难度大致有个数。

祝你玩的愉快！

*关于 Pandas 的 100 题目目前还没有完成！如果你有想反馈或是改进的建议，欢迎提 PR 或是 issue。*

## 难度概览

| 章节                    | 描述                                                         | 难度      |
| ----------------------- | ------------------------------------------------------------ | --------- |
| 导入 Pandas             | 准备好使用 Pandas 吧！                                       | 简单      |
| DataFrame：基础知识     | 使用 DataFrame 进行选择、排序、添加以及聚合数据。            | 简单      |
| DataFrame：更上一层楼   | 有点困难了！你可能需要结合两种或以上的方法才能得到正确的解答。 | 中等      |
| DataFrame：向你发出挑战 | 这里可能需要一点突破常规的思维……                             | 困难      |
| Series 和 DatetimeIndex | 使用时间数据创建和操作 Series 对象。                         | 简单/中等 |
| 清理数据                | 让 DataFrame 更好协作。                                      | 简单/中等 |
| Pandas 多层索引         | 为 Pandas 添加多层索引！                                     | 中等      |
| 扫雷                    | 玩过扫雷吗？用 Pandas 生成数据。                             | 困难      |
| 绘图                    | 探索 Pandas 的部分绘图功能，了解数据的趋势。                 | 中等      |

## 开始

本仓库将提供两种运行的方法：

1. 点击 [Open in Colab](https://colab.research.google.com/github/VXenomac/100-pandas-puzzles-cn/blob/master/) 直接运行

2. 在电脑本地运行

   1. 克隆该仓库到你的电脑

   ```bash
   git clone https://github.com/VXenomac/100-pandas-puzzles-cn
   ```

   2. 安装所需依赖（按需创建虚拟环境）

   ```bash
   pip install -r requirements.txt
   # 如果下载缓慢可换用国内豆瓣 pip 源
   pip install -r requirements.txt -i http://pypi.douban.com/simple --trusted-host pypi.douban.com
   ```

   3. 打开 Jupyter Notebook

   ```
   jupyter notebook --notebook-dir=100-pandas-puzzles-cn
   ```

   现在你应该可以在你的浏览器中看见它们了。

## 其他资料

如果你想在开始之前复习复习 pandas，官方文档是一个不错的选择：

- [10 minutes to pandas](http://pandas.pydata.org/pandas-docs/version/0.17.0/10min.html)
- [pandas basics](http://pandas.pydata.org/pandas-docs/version/0.17.0/basics.html)
- [tutorials](http://pandas.pydata.org/pandas-docs/stable/tutorials.html)
- [cookbook and idioms](http://pandas.pydata.org/pandas-docs/version/0.17.0/cookbook.html#cookbook)
- [Guilherme Samora's pandas exercises](https://github.com/guipsamora/pandas_exercises)