# robosys2022


# plusコマンド
![test](https://github.com/aoi-daiguji/robosys2022/actions/workflows/test.yml/badge.svg)


## このソフトについて
標準入力から読み込んだ数字を足し、結果を出力します。


## 必要なソフトウェア
* Python
  * テスト済み: 3.7〜3.10

## テスト環境
* Ubuntu 22.04


## インストール方法
このリポジトリのURLをコピーし、保存したいディレクトリにクローンしてください。

### コマンド
> git clone https://github.com/aoi-daiguji/robosys2022.git


## コマンドの入出力例
このリポジトリがあるディレクトリに移動します。

### 例
> cd ~/robosys2022

### seqコマンド
指定した数までのすべての整数を代入するseqコマンドを利用して実行します。
#### 例

> seq 5 | ./plus

### 好きな数字を足す
好きな数字を足したい場合は、実行コマンドのうしろに直接書き込んでください。

#### 例
>./plus 2 3 5 7 9 11 13 17 19 57


## 権利表記
* このソフトウェアパッケージは、3条項BSDライセンスの下、再配布及び使用が許可されます。
* © 2022 Daiguji Aoi
