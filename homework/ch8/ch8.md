## 习题8

### 1. 除了 LK 光流之外,还有哪些光流方法?它们各有什么特点?



### 2. 在本节的程序的求图像梯度过程中,我们简单地求了 u + 1 和 u − 1 的灰度之差除 2, 作为 u 方向上的梯度值。这种做法有什么缺点?提示:对于距离较近的特征,变化应该较快;而距离较远的特征在图像中变化较慢,求梯度时能否利用此信息?



### 3. 在稀疏直接法中,假设单个像素周围小块的光度也不变,是否可以提高算法鲁棒性? 请编程实现此事


### 4. (*) 使用 Ceres 实现 RGB-D 上的稀疏直接法和半稠密直接法。



### 5. 相比于 RGB-D 的直接法,单目直接法往往更加复杂。除了匹配未知之外,像素的距离也是待估计的。我们需要在优化时把像素深度也作为优化变量。阅读 [59, 57],你能理解它的原理吗?如果不能,请在 13 讲之后再回来阅读


### 6. 由于图像的非凸性,直接法目前还只能用于短距离,非自动曝光的相机。你能否提出增强直接法鲁棒性的方案?阅读 [58, 60] 可能会给你一些灵感。