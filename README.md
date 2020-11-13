Lines Number
==
```
Author : Yugeta.Koji
Date   : 2020.11.12
```


# Summary
textareaタグや、プログラムコードを記述するelementに、行番号を付与するライブラリ。
大学ノートのように、罫線を付ける機能もあり。（無地も可能）

# Conflict
- jquery-linedtextarea
https://github.com/cotenoni/jquery-linedtextarea

# Issue
- 折返しも行番号が付与されてしまう（現時点で改修目処なし） 2020.11.12
- 既定値以外にはセットできないため、以後バージョンでoption設定できるようにする予定 2020.11.12
- 絶対座標のため、textareaが座標移動する場合に、行番号エレメントがついていかない。
- border-radiusを使うと、スクロールバーで角が隠れる場合がある(chrome)


# Howto
.lines-numberがセットされているelementに対して実行
sampleフォルダのソースを参考

# License
MIT

