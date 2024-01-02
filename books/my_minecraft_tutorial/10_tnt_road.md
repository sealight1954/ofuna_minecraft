---
title: TNT道路を作ろう(つづき)
---
# 長いTNT道路
3.1.ではTNT道路をいつも地面に作るようプログラムしました。

3.2.では、これを太くしました。

3.3.では、これを長くしましょう。

![](/images/10_tnt_road/2023-12-12-05-25-24.png)
*終わりの見えていた道路が、、、*

![](/images/10_tnt_road/2023-12-12-05-27-18.png)
*長くなります。*

長い道路を作るための方法の1つとして、**ループ**を練習しましょう。

:::message
**ループ**とは

同じコードを繰り返し実行したいときに使えるコードブロックです。ループブロックの中にあるプログラムを繰り返します。
![](/images/10_tnt_road/2023-12-12-05-41-35.png)
:::

## ループを練習しよう
長い道路を作る前に、ループを練習しましょう。

前回までに、位置(いち)の練習で作った"minami", "ue"プログラムを作りました。

今回は、いつも東にブロックを作る"higashi"プログラムを作ってみましょう。

![](/images/10_tnt_road/2023-12-13-06-30-25.png)
*座標(ざひょう)目印(めじるし)の赤の方向(東)にブロックを置いた*

ループを使って、東の方向にブロックを何個も置くようにしてみます。

![](/images/10_tnt_road/2023-12-16-23-15-22.png)
*ブロックがどこまでも続く*

"higashi"プログラムを作ってみましょう。

### ループ練習①(さいしょの"higashi"プログラム)

<!-- ***yattemiyo*** -->
:::message
まずは、いつも東に3進んだところにブロックを置く"higashi"プログラムを作ってみましょう。

わからないときは、後の答えを見てみましょう。
:::

- [ ] 1: さいしょの"higashi"プログラムを作る

![](/images/10_tnt_road/2023-12-14-05-43-55.png)
*プログラムブロックの中を埋めてみよう*

### ループ練習①(さいしょの"higashi"プログラム)の答え

![](/images/10_tnt_road/2023-12-14-05-58-09.png)
*東に3進んだところに**白の羊毛**を置く*

### ループ練習②(ループする"higashi"プログラム)

さいしょの"higashi"プログラムで、ブロックを繰り返し置くようにループブロックを入れてみましょう

- [ ] 1. さいしょの"higashi"プログラムにループブロックを入れる

![](/images/10_tnt_road/2023-12-14-06-05-27.png)
*ループブロックを入れてみた。これでよかっただろうか？*

- [ ] 2. ループブロックを入れた"higashi"プログラムを実行してみる

![](/images/10_tnt_road/2023-12-14-06-17-02.png)
*ここで*

![](/images/10_tnt_road/2023-12-14-06-18-10.png)
*こう*

![](/images/10_tnt_road/2023-12-14-06-19-56.png)
*ささやかれました:*

ブロックをたくさん置くことができませんでした。
このプログラムでは、繰り返しはできていますが、毎回**同じ位置**にブロックを置こうとしてしまっています。

繰り返しごとに、ブロックを置く場所をずらしたいです。

- [ ] 3. ブロックを置く場所をずらす

以下の手順で、ブロックを置く場所をずらして、ブロックをたくさん長く配置するようにしましょう。

![](/images/10_tnt_road/2023-12-14-06-25-47.png)
*計算ブロックを東(座標の左)に置く*

<!-- ![](/images/10_tnt_road/2023-12-14-06-26-53.png) -->
![](/images/10_tnt_road/drag_and_drop.png)
*「変数 "カウンター"」の"カウンター"をドラッグ&ドロップ*

![](/images/10_tnt_road/2023-12-16-23-09-47.png)
*計算ブロックの片方に変数(カウンター)を配置*

![](/images/10_tnt_road/2023-12-16-23-27-29.png)
*東に3進んだところから置き始める*

この"higashi"ブロックを実行してみると、たくさんのブロックが置かれることがわかります。

![](/images/10_tnt_road/2023-12-16-23-30-03.png)
*実行前の様子*

![](/images/10_tnt_road/2023-12-16-23-30-27.png)
*ブロックが縦に並んで置かれた*