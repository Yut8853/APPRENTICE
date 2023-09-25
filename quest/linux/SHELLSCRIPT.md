# シェルスクリプトを書くことができる

## 1. Hello

シェルスクリプトのファイルを作成し、「Hello!」と出力してください。

なお、シェルスクリプトを実行する際にはファイルに実行権限が付与されている必要があることに気を付けてください。
→
vim hello.sh
factory@factory:~$ chmod +x hello.sh
factory@factory:~$ ./hello.sh
Hello!

## 2. 標準入力から値を受け取る

シェルスクリプトのファイルに「What's your name?」と出力し、ユーザーに名前の入力を求めます。その後ユーザーが入力した名前に対して、「Welcome, $name!」（$name は入力された名前）と出力する処理を追加してください。
→
vim welcome.sh
factory@factory:~$ chmod +x welcome.sh
factory@factory:~$ ./welcome.sh
What's your name?
yutaka
Welcome, yutaka


## 3. 条件分岐

四則演算を行う電卓を作成してください。実行すると以下の挙動になります。

```bash
Enter two numbers:
10 # ユーザーが入力
11 # ユーザーが入力
Choose an arithmetic operation (+, -, *, /):
+ # ユーザーが入力
The result:21
```

なお、割り算の時の割る数が 0 であるケースや、演算子の記号 +, -, *, / が合致しないケースを考慮するかは任意とします。
→
 vim calculator.sh
factory@factory:~$ chmod +x calculator.sh
factory@factory:~$ ./calculator.sh
I'll do the mesh,put in two numbers:
2
3
choice (+,-,*,/):
+
result: 5
factory@factory:~$ ./calculator.sh
I'll do the mesh,put in two numbers:
3
2
choice (+,-,*,/):
-
result: 1
factory@factory:~$ ./calculator.sh
I'll do the mesh,put in two numbers:
4
4
choice (+,-,*,/):
*
result: 16
factory@factory:~$ ./calculator.sh
I'll do the mesh,put in two numbers:
6
3
choice (+,-,*,/):
/
result: 2
factory@factory:~$ ./calculator.sh
I'll do the mesh,put in two numbers:
6
5
choice (+,-,*,/):
/
./calculator.sh: line 18: [5: command not found
result: 1

## 4. 繰り返し処理

for 文 または while 文を利用して、1~100までのうち、偶数の数字を表示する処理を書いてください。以下の結果が出力されます。

```bash
2 4 8 ... 100
```
→
vim even100.sh
factory@factory:~$ chmod +x even100.sh
factory@factory:~$ ./even100.sh
2 4 6 8 10 12 14 16 18 20 22 24 26 28 30 32 34 36 38 40 42 44 46 48 50 52 54 56 58 60 62 64 66 68 70 72 74 76 78 80 82 84 86 88 90 92 94 96 98 100 

