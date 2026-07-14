---
layout: post
title: pyxel 角丸の四角形を描く
tags: [PYXEL]
img_dir: /assets/img/2026-07-14-pyxel_rouded_rectangle/
---

### 角丸を描きたい
pyxelでは、デフォルトでpyxel.rectが提供されており、四角形を描くことができます。  
しかし、実際に四角形を書く時は、少し角を丸くしたりしたいものです。（？）  
そんな時用に関数を作成しました。

draw_rrectが塗りつぶし、
draw_rrectbが枠線のみです。

<script src="https://gist.github.com/okapping/6f90467210f67c16320f56c2ee50c4e9.js"></script>


若干苦戦したポイントは、角の円を描画する際に
pyxel.clip(x, y, w, h)で、角っこのみを描画していることです。


![入力例](/assets/img/2026-07-14-pyxel_rouded_rectangle//image1.png)

### PyxelCodeMakerに上げてみた
PyxelCodeMakerで書いて、SaveボタンからGistで保存すると、PyxelCodeMakerのリンクで共有が可能になるようです。  
というわけで下記PyxelCodeMakerにて上記関数のチェック可能です。  
[PyxelCodeMaker](https://kitao.github.io/pyxel/web/code-maker/?gist=7ce88fec575cb3ac71439b3475b8e2d8)


