# CurriculumDesign
图的遍历：广度优先遍历、深度优先遍历。
对于广度优先遍历应利用队列的五种基本运算（置空队列、进队、出队、取队头元素、判队空）来实现。首先建立一空队列，从初始点出发进行访问，当被访问时入队，访问完出队。并以队列是否为空作为循环控制条件。
对于深度优先遍历则采用递归或非递归算法来实现。其中，对于图的非递归深度优先遍历应利用栈的五种基本运算（置空栈、压栈、出栈、取栈顶元素、判栈空）来实现。首先建立一空栈，从初始点出发进行访问，当被访问时入栈，访问完出栈。并以栈是否为空作为循环控制条件。
有向图定义结点时，添加入度和出度，分别统计每个节点的入度和出度。Visited变量若全为1，则连通且无回路；若有为0的，则不连通；若有大于1的，则有回路。
