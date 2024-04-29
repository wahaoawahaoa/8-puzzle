![image](https://github.com/wahaoawahaoa/8-puzzle/assets/119476786/9a55eaa1-8ead-4e04-b631-edec77a7e514)# 8-puzzle

八数码问题也叫九宫问题，是人工智能中状态搜索中的经典问题，其中，该问题描述为：在3×3的棋盘，摆有八个棋子，每个棋子上标有1至8的某一数字，不同棋子上标的数字不相同。棋盘上还有一个空格，与空格相邻的棋子可以移到空格中。要求解决的问题是：给出一个初始状态和一个目标状态，找出一种从初始转变成目标状态的移动棋子步数最少的移动步骤。本题中采用9位字符串来表示每一个状态，其中0表示空方块，例如283104765表示如下状态

![image](https://github.com/wahaoawahaoa/8-puzzle/assets/119476786/5e162203-436b-4014-b8d5-d09af530d58c)

本项目采用BFS,DFS,Heuristic search三种搜索方法对其进行解决
自行设计或随机生成3组输入样例S，输出最终结果，包含从S->D每一步的过程；
在文档中给出代码、输入输出样例，简单说明代码逻辑；
测算三种解法的性能，分析其优缺点
