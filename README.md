# Tetris_cmd

## 程序简介
以C++编写的使用命令行界面模拟俄罗斯方块的程序。
目前只完成了基础操作部分，目前代码量约900+行，预计完成项目代码量约1300+行。（双人对战模式令加700+行）

## 运行要求
首次使用时Windows 8 / 10需将CMD的“使用旧版控制台”打开，“快速插入”和“快速编辑模式”关闭。运行CMD窗口时关闭输入法。

## 操作介绍
开始界面使用方向上下或W和S键操作光标。

### 单人模式键位：
A：左移
D：右移
S：下降
W：硬降
Q：左转
E：右转

## 已完成内容：
### 单人模式下的：
- 新方块刷新
- 方块的自动下落
- 左移、右移、左转、右转操作
- 下降、硬降操作（下落+移动同时操作时可能有BUG）
- 下落方块检测并刷新新方块
- 整行填满消除的判断
- 最顶行的Game over判断（可能有BUG）

## 待完成内容：
### 单人模式下的：
- 分数计算
- 即将出现的后N个方块的缓存区
- HOLD
- 键位自定义
- 屏幕刷新闪屏双缓存优化
- 天梯榜
- 操作延迟优化

### 多人模式下的：
- 双人同时操作的基本功能实现
- 对战分数计算
- 消除行的对方惩罚
- 天体榜

### 其他
- 键位自定义
- 游戏区域大小自定义

## Something else
- 由于基础代码设计缺陷，目前Game over的判断为顶部两行有放置的方块即为游戏结束。