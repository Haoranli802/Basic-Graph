# Basic-Graph

LC130 被包围的区域

思路：有点像岛屿问题被海水包围的岛屿，首先我们先沿着边界吧所有靠边界的岛屿做特殊标记，然后遍历整个图，如果找到未被特殊标记的岛屿那么我们把它淹掉，如果找到特殊标记的岛屿那么把它转换成普通岛屿。
