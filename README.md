# Javaの世界へようこそ
このレッスンでは、Javaの基本的なコードの書き方、出力について学んでいきます。

### 文字を出力してみよう
`System.out.println` を使って文字をコンソールにだしてみよう。


##### コーディング

1. `Greeting.java` ファイルを作成
2. `Greeting.java` に以下の内容を書き写す

```java
class Greeting {
  public static void main(String[] args) {
    // あいさつ
    System.out.println("はろー");
  }
}
```

##### 実行
1. コマンドプロンプトを立ち上げる
2. 以下のコマンドを実行

```console
$ javac Greeting.java
$ java Greeting 
$ はろー
```

### TODO
- [ ] `Hello world!` を出力してみよう
- [ ] 出力を確認できたら commit & push をしてみよう
- [ ] 実行結果が緑色になることを確認しよう 
