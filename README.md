# TorusInnerDiameter
寻找网格剖分后表达环体内环的三角形组

环体是游泳圈形状，规则目标

剖分前预先手动add一个能表达内径的边缘线（处在xoy面上，半径是torus的内径尺寸，中心点为原点的正圆），使得剖分所得的三角形们沿此边缘排布

由于torus和sphere拓扑不同，所以网格剖分后，LS的个数多了两个，多的是2个Loop

此段代码添加到选取LS基函数的文件里

后续步骤和sphere计算一致
