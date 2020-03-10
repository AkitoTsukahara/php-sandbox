# php-sandbox
簡単なPHPを動かす為の環境がサクッと作れるよ！


# 始め方
1.このリポジトリをクローンもしくはダウンロードしてください。

2.（DBを使いたい場合)`docekr-compose.yml`のコメントアウトを外してください。

3.`php-sandbox`ディレクトリで以下のコマンドを入力してください。
  ```
$ docker-compose up -d
  ```
  
4.`http://localhpst:8080`を開いてphpinfoが表示されていれば成功です！

止めたい時は以下のコマンドを入力してください。
```
$  docker stop $(docker ps -q) 
```