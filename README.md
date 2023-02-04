# Dancing☆Onigiri 9tkey
9tkeyは[FUJI](https://kt-rpg.sakura.ne.jp/)さんが考案したテンキーを使用するプレイスタイルです。
[Dancing☆Onigiri (CW Edition)](https://github.com/cwtickle/danoniplus)のカスタムjs機能で再現しました。

## 使い方
Dancing☆Onigiri (CW Edition)のjs/cssフォルダに各ファイルを配置してください。
- js/danoni_custom_9t.js
- css/9tkey.css

9keyとして譜面を作成し、以下の定義を追加してください。
```
|customjs=*,danoni_custom_9t.js|
|customcss=9tkey.css|
|motionUse=false|
|appearanceUse=false|
|maxSpeed=20|

|keyExtraList=9t|
|chara9t=left,down,up,right,space,sleft,sdown,sup,sright$9t_0|
|color9t=0,0,0,0,2,0,0,0,0$9t_0|
|shuffle9t=0,0,0,0,1,0,0,0,0$9t_0|
|stepRtn9t=45,90,135,0,onigiri,180,-45,-90,-135$9t_0|
|div9t=9$9|
|pos9t=9A_0$9A_0|
|keyCtrl9t=103/0,104/0,105/0,100/0,101/0,102/0,97/0,98/0,99/0$55/0,56/0,57/0,85/0,73/0,79/0,74/0,75/0,76/0|
|scale9t=1$1|

|arrowMotion_data=
0,20,arrow9t,arrow9t-rev
0,22,arrow9t,arrow9t-rev
|
```

## その他
リポジトリ内に以下のファイルを同梱しています。
- 9t.json
  - SKBさんの[Dancing☆Onigiri エディター](https://github.com/superkuppabros/danoni-editor)用の設定ファイルです。
- dos_example.js
  - 譜面データのサンプルです。
