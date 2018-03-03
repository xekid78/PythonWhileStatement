# PythonWhileStatement
while文

## 処理
<dl>
  <dt>ケース１</dt>
  <dd>１～５の数字を昇順に「**だよ。」と出力する。</dd>
  <dt>ケース２</dt>
  <dd>１～５の数字を降順に「**だよ。」と出力する。</dd>
</dl>

## コード
```
print("** ケース１ **")
i = 1
while i <= 5:
    print(str(i) + "だよ。")
    i += 1
print("")
print("** ケース２ **")
i = 5
while i >= 1:
    print(str(i) + "だよ。")
    i -= 1
```

## 出力結果  
```
** ケース１ **
1だよ。
2だよ。
3だよ。
4だよ。
5だよ。

** ケース２ **
5だよ。
4だよ。
3だよ。
2だよ。
1だよ。
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Python 3.6.4 |
