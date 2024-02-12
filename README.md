# Github CodespacesでJupyter Notebookを使ってみる

CodespacesのVSCode上でJupyter Notebookを使う方法。  
foliumで地図を表示してみる。

## 実行手順

1. リポジトリでCodeをクリック
2. Codespacesタブを開く
3. "+"をクリック

以上でVSCodeが立ち上がる。
ターミナルからコマンド実行も可能。

jupyter関連のコマンドは既にインストール済。

```
$ jupyter
jupyter               jupyter-execute       jupyter-lab           jupyter-migrate       jupyter-server        
jupyter-dejavu        jupyter-kernel        jupyter-labextension  jupyter-nbconvert     jupyter-troubleshoot  
jupyter-events        jupyter-kernelspec    jupyter-labhub        jupyter-run           jupyter-trust
```

VSCode上でコードを入力。

この状態ではセルのコードを実行する時にカーネルが選択できなかったので、
拡張機能からJupyter(Microsoft)をインストール。  
これで実行可能となる。

foliumをpipでインストール。
```
pip install folium
```

foliumのサンプルコードは以下を参照。

Python: foliumでJupyter Notebookに地図を描画する
https://ohke.hateblo.jp/entry/2018/03/02/230000

以上。