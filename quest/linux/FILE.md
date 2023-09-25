# ファイルを操作できる

## 1. ファイルの中身を出力

/etc/hosts ファイルの中身を出力してください。/etc/hosts ファイルが存在しない場合は、何らかのテキストファイルの中身を出力してください。
→
-rw-r--r-- 1 root adm 222 Sep 24 01:37 hosts

## 2. ファイルの中身をスクロール表示

/etc/hosts ファイルの中身をスクロール式で表示してください。/etc/hosts ファイルが存在しない場合は、何らかのテキストファイルの中身を表示してください。
→
less /etc/hosts

127.0.0.1 localhost
127.0.1.1 factory

# The following lines are desirable for IPv6 capable hosts
::1     ip6-localhost ip6-loopback
fe00::0 ip6-localnet
ff00::0 ip6-mcastprefix
ff02::1 ip6-allnodes
ff02::2 ip6-allrouters


## 3. ファイルの作成

ホームディレクトリの直下に、README.md という名前の空ファイル（中身が空のファイル）をコマンドを利用して作成してください。
→
touch README.md
ls
Desktop    Downloads  Pictures  README.md  Templates
Documents  Music      Public    snap       Videos


## 4. ファイル名の変更

先程作成した README.md ファイルの名前を TMP.md という名前に変更してください。
→
mv README.md TMP.md
factory@factory:~$ ls
Desktop    Downloads  Pictures  snap       TMP.md
Documents  Music      Public    Templates  Videos


## 5. ファイルのコピー

先程作成した TMP.md ファイルをコピーして COPY.md ファイルを作成してください。
→
cp TMP.md COPY.md
factory@factory:~$ ls
COPY.md  Documents  Music     Public  Templates  Videos
Desktop  Downloads  Pictures  snap    TMP.md

## 6. ファイルの削除

先程作成した TMP.md ファイルを削除してください。
→
rm TMP.md
factory@factory:~$ ls
COPY.md  Documents  Music     Public  Templates
Desktop  Downloads  Pictures  snap    Videos

## 7. シンボリックリンク

作成した README.md に対して、シンボリックリンクを貼ってください。シンボリックリンクのファイル名は README_SYMBOLIC.md としてください。作成後、README.md に対して任意の文章を追記してください。その後、symbolic_file の中身を出力し、追記した内容が README_SYMBOLIC.md にも反映されていることを確認してください。
→
ln -s README.md README_SYMBOLIC.md
factory@factory:~$ echo 'symbolic-test' >> README.md
factory@factory:~$ cat README_SYMBOLIC.md
symbolic-test
factory@factory:~$ ls
COPY.md  Documents  Music     Public     README_SYMBOLIC.md  Templates
Desktop  Downloads  Pictures  README.md  snap                Videos

## 8. ファイルの検索

ホームディレクトリ以下のファイルに対して、README という文字列が含まれるファイルを全て検索し、出力してください。なお、find コマンドを使用して実現することができます。
→
find ~ type f -name 'README*'
/home/factory/README.md
/home/factory/README_SYMBOLIC.md
find: \u2018type\u2019: No such file or directory
find: \u2018f\u2019: No such file or directory

## 9. 検索

~/sample.txt ファイルを作成し、以下の内容を記載してください。

```bash
apple
banana
grape
lemon
```

→
$ printf "apple\nbanana\ngrape\nlemon" > ~/sample.txt
factory@factory:~$ cat ~/sample.txt
apple
banana
grape
lemon

その上で、sample.txt ファイルから、"a" で始まる単語を検索してください。なお、grep コマンドを使用して実現することができます。
→
 grep '^a' ~/sample.txt
apple

