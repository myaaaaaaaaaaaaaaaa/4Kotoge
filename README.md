# 4Kotoge

上から落ちてくるだけの音ゲー（？）
EatKanoが面白かったのでローカルで実行可能なhtml(js)ゲームを生成した（AIが）

EatKano → https://github.com/arcxingye/EatKano?tab=readme-ov-file

製作日数合計：5日くらい

### ゲームの詳細

PERFECTは45msみたいです　やさしい


iPadでの操作を想定しているが、PCのDFJKキーでも操作できる　PCだと軽い

~~Googleや特にSafariだとダブルタップで拡大されちゃうかも　あと重いと思う~~　←大丈夫だよ　①だけダメかも

ローカルにダウンロードしてHTMLviewerなどで実行してください

-----
### ベータ版

①2代目　DOM処理+ローカルのmp3から音を出すもの（mp3は外した）　だと思う　普通に面白い（重いけど）

https://myaaaaaaaaaaaaaaaa.github.io/4Kotoge/4Kotoge/index_mobile.html

②これが基礎　Canvasに切り替えて音もWeb APIにした 軽量化のためいったんスコアも廃止 ノーツタイプももう追加されている　こだわり　完全な練習モード

https://myaaaaaaaaaaaaaaaa.github.io/4Kotoge/4Kotoge/nazo.html

③こっちは自動でおすすめの設定にしてくれるもののベータ版　アイデアは良かったと思う

https://myaaaaaaaaaaaaaaaa.github.io/4Kotoge/4Kotoge/auto.html

---
### 完成版
好きな見た目に寄せるために奮闘（12時間かかったほんとに疲れたでもできてよかった）
・最近の音ゲーみたいな奥行きを再現
・4K以上も作った

それしかしてないのにロジックのエラーに時間かかりすぎ

~~Edgeでは無反応が多発するため動かないし、ローカルでも謎のMISSが出ることがある　使えない　見た目は好きだけど　　おそらく処理落ちだと思うけど　　判定が追い付いてない~~

できた　判定の処理がおかしかった　奥行きを持たせるためにパース？計算してて、なんかそん時に判定ラインのロジックがぶっ壊れて最新のノーツを判定するようになってた　2つ流れてきたら上のやつを参照するから確定でMISSになるっていう
大晦日に何やってんだマジで　こいつ2026年の初夢だったらもう最悪だよほんと

↓　※ Safariだとまだ無反応がある　もうわかんないしブラウザでは動かさないのでいいや　DLして

https://myaaaaaaaaaaaaaaaa.github.io/4Kotoge/4Kotoge/malonazo.html

-----

### 今後
~~5K~10Kまで作れるかも　と今思った　モード別の処理分け大変そう~~　←できた

せっかくだしスコアも出せるようにしたいけど重くなりそう　こっちは無理かも　canvasでどの程度軽くなったのかがよくわかんない

↑canvasは相当軽いよ　処理追加しまくってもDOM処理の時みたいにカクカクしたことが今のところ一度もない
###
