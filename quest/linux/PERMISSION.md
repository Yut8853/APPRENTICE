# パーミッションを操作できる

## 1. ファイルのオーナーとグループ

ホームディレクトリの直下に、README.md という名前の空ファイルを作成してください。

その上で、README.md ファイルのオーナーとグループを確認してください。
→
factory@factory:~$ touch ~/README.md
factory@factory:~$ ls -l ~/README.md
-rw-rw-r-- 1 factory factory 14 Sep 25 05:12 /home/factory/README.md


## 2. ファイルのパーミッション

README.md ファイルのパーミッションを確認し、誰に何の権限が付与されているかを説明してください。
→
ファイルのオーナー（所有者）： factory
ファイルのグループ： factory

パーミッション
パーミッション文字列： -rw-rw-r--
パーミッションの部分を詳細に見ると、次のようになります。

rw-：オーナーのパーミッションで、読み取り・書き込みが可能を意味します。
rw-：グループのパーミッションで、読み取り・書き込みが可能を意味します。
r--：その他のユーザーのパーミッションで、読み取りのみ可能を意味します。
詳細な説明
factory ユーザーは、このファイルを読んだり書いたりすることができます。

## 3. ファイルのパーミッションの設定

README.md ファイルのオーナーに対して、読み取り、書き込み、実行の全ての権限を付与してください。
→
factory@factory:~$ ls -l ~/README.md
-rwxrw-r-- 1 factory factory 14 Sep 25 02:12 /home/factory/README.md

## 4. ディレクトリのパーミッションの設定

ホームディレクトリの直下に、permission という名前の空ディレクトリを作成してください。

permission ディレクトリのグループに対して、書き込み権限を付与してください。
→
factory@factory:~$ mkdir ~/permission
factory@factory:~$ chmod g+w ~/permission
factory@factory:~$ ls -ld ~/permission
drwxrwxr-x 2 factory factory 4096 Sep 25 02:49 /home/factory/permission

## 5. スーパーユーザー

スーパーユーザーとして、ホームディレクトリの直下に superuser という名前の空ディレクトリを作成してください。

作成後、superuser ディレクトリのオーナーが誰かを確認してください。
→
factory@factory:~$ sudo mkdir ~/superuser
[sudo] password for factory: 
factory@factory:~$ ls -ld ~/superuser
drwxr-xr-x 2 root root 4096 Sep 25 02:52 /home/factory/superuser
