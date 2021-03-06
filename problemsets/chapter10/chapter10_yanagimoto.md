## 10.3 （柳本）
### (a) 真
$5n^3 \in O(n^3) = O(n^3\log n)$
### (b) 偽
階乗は指数関数を支配する。
### (c) 真
$\text{DT}(\log(5n^3 + n \log n)) \rightarrow \log(\text{DT}(5n^3 + n \log n)) = \log(5n^3) \in O(\log n)$
### (d) 真
$\log n \in O(\log(5 n^3)) = O(\log(5n^3 + n\log n))$
### (e) 真
たかだか6乗
### (f) 真
10.2.3節より、多項式関数は準指数関数
### (g) 偽
定義から多項式時間
### (h) 偽
階乗は指数関数を支配するので、準指数関数を支配する
### (i) 真
階乗は指数関数を支配するので、指数関数が超多項式時間であることから

## 10.8　（柳本）
$O(n^3(\log n)^4)$

**証明**
10.5節の結果を用いて、
1. このPythonプログラム$P$をランダムアクセスTMでシミュレートするとき$O(n\log n)$
2. マルチテープTMでシミュレートする時、$O((n\log n)^3) = O(n^3(\log n)^3)$
3. マルチテープ万能TMでシミュレートする時、$O(n^3(\log n)^3 \log(n^3 (\log n)^3)) = O(n^3(\log n)^4)$


## 10.13 （柳本）
$O\left(n^2\sqrt{10}^n\right)$

**証明**
- 解は明らかに、$O(n^2\sqrt{M}/2) = O(n^2\sqrt{M})$
- $\sqrt{M} = O(10^x)$ とすると、$M = O(10^{2x})$
- $M = O(10^n)$より、$x = \frac{1}{2}n$かつ、$\sqrt{M} =O\left(\sqrt{10}^n\right)$

