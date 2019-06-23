mapreduce-wordcount-sample
----

入力テキストの準備方法

```
mkdir -p input
curl -L http://www.gutenberg.org/cache/epub/2266/pg2266.txt > input/pg2266.txt
```

WordCountプログラムの実行方法

```
rm -rf output
gradle run
```

結果の確認方法

```
cat output/*
```
