[工学基礎シリーズ オペレーティングシステム（オーム社）](https://www.ohmsha.co.jp/book/9784274229152/) に掲載しているプログラムのソースコードです．

Linux や macOS などのUnix系OSで動作します．
Windows では WSL2 などを使って Linux 環境を作って実行して下さい．

Makefile を用意しておいたので，C言語のプログラムはソースコードを展開したディレクトリで make コマンドを実行するとコンパイルできます．

Makefile は GNU make の書式で書いてあります．
ターミナルから `make -v` を実行して GNU Make と表示されればOKです．
デフォルトではC言語のプログラムのみをコンパイルします．
Java言語のプログラムもコンパイルする場合は，`make COMPILE_JAVA=1` のようにして下さい．

Cコンパイラやmakeコマンドのインストール方法についてはネット上の記事などを参照して下さい．

# 2章
## stackframe.c
p.26 スタックフレームの確認用プログラム (C言語).  
Makefile では gcc (GNUのCコンパイラ) を使って，図2.3を出力する際に用いたオプションでコンパイルするようになっています．

# 3章
## pthread.c
p.55 Pthreadによるマルチスレッドプログラム.

## prod-cons-semaphore.c
p.76 セマフォを用いた生産者／消費者問題のプログラム.

## prod-cons-mutex.c
pp.79-80 mutexと条件変数を用いた生産者／消費者問題のプログラム.
## ProducerConsumer.java
p.81 Javaによる生産者・消費者問題のプログラム.
## deadlock.c
p.82 デッドロックが発生するプログラム例.
## exercise3-3.c
p.85 演習問題3のプログラム.
