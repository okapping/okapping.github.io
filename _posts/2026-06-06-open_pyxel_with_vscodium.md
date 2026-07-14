---
layout: post
title: VSCodiumで、VSCodeの拡張機能、pyxelを開けるようにする
tags: [VSCodium]
---

VSCodiumは、VSCodeのオープンな部分だけで作成されたVSCodeです。  
そんなVSCodiumにも拡張機能を入れることができますが、  
VSCodeの拡張機能をVSCodeと同じように検索して入れることはできません。

そこで、VSCodeの拡張機能の、VSIXファイルをダウンロードして、それをVSCodiumから開く形で、VSCodiumから使えるようにします。

### VSIXファイルをダウンロードする
まず[こちらのサイト](https://cypherpunksamurai.github.io/vsix-downloader-webui/)にて、pyxelと検索し、
右側のボタンから、「Universal」を選択。

![入力例](/assets/img/2026-06-06-open_pyxel_with_vscodium/image_1.jpg)

### VSCodiumで開く
拡張機能を開き、三点リーダー「…」から「VSIXからのインストール」を押し、先ほどダウンロードしたファイルを開いて完了
![入力例](/assets/img/2026-06-06-open_pyxel_with_vscodium/image_2.jpg)

### 終わり
pyxelを自身がダウンロードしたい拡張機能名に置き換えることで動作すると思います。

最初のリンクを見つけるのに若干苦労したため、ここに書き残します。

VSCode拡張機能の公式ページからVSIXがダウンロードできるようになるといいのにと思いました。

VSCodiumでpyxelを開きたい人に届いてくれれば幸いです。