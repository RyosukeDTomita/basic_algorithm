# サーチアルゴリズムまとめ

## 線形探索(Liner Search)

- 先頭から対象となる値を探す。
- 計算量は O(n)。

### 線形探索 with 番兵法(Sentinel loop)あり

- 前提として線形探索においてループの終了条件は，以下の 2 つがある。
  - 探索する値が見つかったか
  - 探索する値が見つからなかった場合に配列の末尾に到達したか
- 探索する配列に番兵として探索する値を末尾に追加することで，必ず探索する値が見つかるようになるため，ループの終了条件を探索する値が見つかったかの 1 つにすることができる。

---

## 2 分探索(Binary search)

- 配列を半分にわけて，ピボットを基準にターゲットとなる値が左右のどちらにあるか探索する。
- 配列がソート済みであることが必要。

- 計算効率は、1 ステップごとに探索対象が半分になっていく。これは 2 進数においては 1 桁減ることを表しているので計算量は O(log2 n)と表せる。

---

## bit 全探索(bit search)

---

## 順列全探索(Permutation search)

---

## 深さ優先探索(Depth First Search)

---

## ｈ幅優先探索(Breadth First Search)

---

## 2 分木探索(Binary search tree)
