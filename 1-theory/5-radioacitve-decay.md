# 5. 放射性崩壊
{% include use-katex.html %}
## 崩壊の種類
- 原子核を繋ぎ止める力は強いが遠くまで届かない<br/>→原子核が大きい元素ほど不安定
- 不安定な元素は時間が経つと崩れて安定な元素になっていく
- 崩れ方は3パターンある

### $\alpha$ 崩壊
ヘリウム原子核($\alpha$ 線)を出す。

### $\beta$ 崩壊
中性子→陽子+電子 に変わり、電子($\beta$ 線)を出す。

### $\gamma$ 崩壊
$\alpha$ 崩壊や $\beta$ 崩壊後の、不安定な(エネルギーが高い)状態の原子が安定になるときに、差分のエネルギーが電磁波($\gamma$ 線)として出る。

## 崩壊の速さ
- 崩壊の速さは **指数関数** 。<br/>→全体の量が $x$ 倍になる期間が決まっている<br/>($0<x<1$)
- 特に全体の量が半分になる期間は **半減期** と呼ばれる

## 参考
### なぜ崩壊は指数関数的速さなのか
(単位時間あたり崩壊する個数) ∝ (崩壊していない総量)
<br/>(確率的な話(?))

(以下 $A,B,C,D$ は初期状態や原子の種類によって決まる定数)

個数を $N$ として
$$-\frac{dN}{dt}=CN$$
$$-\frac1N\cdot\frac{dN}{dt}=C$$
両辺を $t$ で積分。
$$-\log N=Ct+D$$
$$N=-e^{Ct+D}$$
$A=e^D, B=e^C$ として
$$N=AB^t$$