# Vokaloid-Stimmforschung
## このリポジトリの概要
このリポジトリは、新しい歌声合成エンジンを制作するための研究資料及び、プログラム群です。

## 論文の場所
このリポジトリで制作された論文は以下にあります。
https://1drv.ms/o/s!AuwQM44QVxDQg6EZnsVPkMLqjRUy6Q?e=YuXBrz

## ソフトウェアの開発について
見切り発車で開発を進めてますが、どのような方向性で進めているかを記述してます。

使用フレームワーク：NIH-plug
→使用言語：Rust
DAWからMidiデーターを受け取り、チューニングファイルを読み込んで、シンセサイザーとして波形を返す感じ。

## 収録している発音記号
|文字|母or子|有or無|音韻|補足|
|---|---|---|---|---|
|ん|子|有|/n/ /m/  /ɴ/  /ŋ/ etc.|https://ja.m.wikipedia.org/wiki/%E3%82%93|
|---|---|---|---|---|
|あ|母|有|/ä/|https://ja.m.wikipedia.org/wiki/%E3%81%82|
|い|母|有|/i/|https://ja.m.wikipedia.org/wiki/%E3%81%84|
|う|母|有|/u/|https://ja.m.wikipedia.org/wiki/%E3%81%86|
|え|母|有|/e/|https://ja.m.wikipedia.org/wiki/%E3%81%88|
|お|母|有|/o/|https://ja.m.wikipedia.org/wiki/%E3%81%8A|

