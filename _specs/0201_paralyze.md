---
title: パラライズ
---
## 概要
* 一部の攻撃を食らった時に増加する
* 格闘ゲームでいうところのピヨり値

今作ではパラライズ値とパラライズ最低値の2つを用意する。

## 増減
攻撃を食らった時にパラライズ値とパラライズ最低値が増加する。

* パラライズ値は時間経過でパラライズ最低値まで減る。
* パラライズ最低値は時間経過でゆっくりと0まで下がる。

バースト時にどちらもリセットされる

## 効果
パラライズ値が最大までたまると[スタン](0202_stun.md)に移行する。

パラライズ値がパラライズ最低値を超えている間は弱パラライズ状態になる。
弱パラライズ状態では以下の影響を受ける。
* 移動速度の低下
* 旋回速度の低下