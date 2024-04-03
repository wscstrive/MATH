# Notes



## Cramer‘s Rule, Inverse, and Volumes

### 行列式公式的证明

<img width="1136" alt="image" src="https://github.com/wscstrive/MATH/assets/101634608/08d1995d-6a75-47ef-a1c0-21fd927aa7c8">

<img width="982" alt="image" src="https://github.com/wscstrive/MATH/assets/101634608/823913f2-d80c-46db-97e2-3c5f3203874d">

> 不难发现，等式右边的对角线上都是子式与它对应的 代数余子项，对于其他为0需要解释

<img width="537" alt="image" src="https://github.com/wscstrive/MATH/assets/101634608/58a4ba5d-0c36-4a6e-a97f-3d2fc3daf959">

> 需要想象一下，等式左侧的 代数余子项 没有发生，变化的是前面的子式，而子式的改变不会影响到代数余子项，因此可以把公式（7）中的第一行换成等式左侧左侧子式的形式，从行列式看出，这个行列式存在相同的行向量，也就意味着 行列式=0

### Cramer‘s Rule

- 对于克拉默法则，首先考虑Ax=b的形式

<img width="504" alt="image" src="https://github.com/wscstrive/MATH/assets/101634608/f69664f6-e525-4019-8289-2a2d4eee120c">

> 右侧的Ctb可以看做是行列式公式的特殊矩阵，那就是对于每一行b向量与对应的 代数余子式的行列式B的解，可以理解Ctb=det（B）

### Volumes

- 行列式的结果其实就是每个向量的相乘=维度形状的体积，对于三维单位矩阵，就是1 * 1 * 1
