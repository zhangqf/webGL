# 高级变换与动画基础

1. 学习使用一个矩阵变换库，该库封装了矩阵运算的数学细节
2. 快速上手使用矩阵库，对图形进行复合变换
3. 在该矩阵库的帮助下，实现简单的动画效果


## 平移 然后旋转

`Matrix4`对象表示一个4x4的矩阵。该对象内部使用类型化数组`Float32Array`来存储矩阵的元素
