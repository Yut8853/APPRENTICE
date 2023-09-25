# 標準入出力を扱える

## 1. 標準入出力とは

標準入力、標準出力、標準エラー出力について、プログラミング初心者にわかるように説明してください。
→
コンピュータ（パソコン）が動作する場合に人間と会話する際に３つの基本的な会話があります。
まず
標準入力はプログラムに入力すること、例えばキーボードからテキストを入力することです。

標準出力は入力されたプログラムが外部に出力されること、例えば計算結果を画面に表示すること

標準エラー出力は出力の一種ですがこちらはエラーメッセージなどを出力するために使われます。

## 2. リダイレクト

リダイレクトを使用して、ルートディレクトリを ls コマンドで出力した結果を、~/root.txt という新規ファイルに保存してください。
→
touch root.txt
factory@factory:~$ ls / > ~/root.txt
factory@factory:~$ cat root.txt
bin
boot
dev
etc
home
lib
lost+found
media
mnt
opt
proc
root
run
sbin
snap
srv
swap.img
sys
tmp
usr
var
factory@factory:~$ 

## 3. エラー出力のリダイレクト

コマンドを実行してエラーになった際に、エラー結果を ~/error.txt という新規ファイルに保存してください。エラーを発生させるにはは例えば ls /hoge など、存在しないファイル・ディレクトリを ls コマンドで参照する方法があります。
→
ls /hoge 2> ~/error.txt
factory@factory:~$ cat error.txt
ls: cannot access '/hoge': No such file or directory

## 4. 出力とエラー出力のリダイレクト

ルートディレクトリと存在しないファイルを ls コマンドで一度で参照しようとして( ls / /hoge )、その両方の結果を一度に ~/result.txt という新規ファイルに保存してください。
→
ls / /hoge > ~/result.txt 2>&1
factory@factory:~$ cat ~/result.txt
ls: cannot access '/hoge': No such file or directory
/:
bin
boot
dev
etc
home
lib
lost+found
media
mnt
opt
proc
root
run
sbin
snap
srv
swap.img
sys
tmp
usr
var

## 5. /dev/null とは

/dev/null とは何で、どういう時に使われるものかをプログラミング初心者にわかるように説明してください。
→
/dev/nullは、コンピュータの「ゴミ箱」のようなものです。コンピュータが出す不要なもの（情報やメッセージ）を、このゴミ箱に入れると、消えてなくなります。
また、ゴミ箱の中を見ても、何も出てきません。不要なものをすっきりさせるために使います。


## 6. /dev/null へのリダイレクト

ルートディレクトリを ls コマンドで参照した結果を、/dev/null にリダイレクトし、何も表示されないことを確認してください。
→
ls / > /dev/null

## 7. パイプライン

ルートディレクトリを ls コマンドで参照した結果のうち、"l" から始まるものだけを、パイプラインを使用して一回のコマンドで表示してください。
→
factory@factory:~$ ls / | grep '^l'
lib
lost+found
