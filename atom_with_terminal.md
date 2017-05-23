MacのターミナルからAtomでファイルを開く方法を調べたのでメモ

##H2 準備
Atomを起動して、Atom > Install Shell Commandsでatomとapmをインストールする。

##H2 方法

- Atomを開く
```$ atom```

- 今いるディレクトリ内でAtomを開く
```$ atom .```

- 特定のディレクトリ内でAtomを開く
```$ atom folder_name```

- 特定のファイルをAtomで開く
```$ atom file_name``` (指定のファイルがなければ新規で作成される)

例：desktopにいる時に、新規ディレクトリhogeを作成+その中に新規ファイルhoge.jsを作成。
```desktop (ユーザ名)$ atom ./hoge/hoge.js```

##H2 参考
- [How to open Atom editor from command line in OS X?](http://stackoverflow.com/questions/22390709/how-to-open-atom-editor-from-command-line-in-os-x)
- [ターミナルから、Atomを起動してみたら便利だった。](http://qiita.com/35_267_/items/5d7afff691477a24742a)
