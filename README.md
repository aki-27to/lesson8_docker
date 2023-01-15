■実施事項
# 第8回課題
## とにかく動かすことを目標とする。
- ちょっと詰まった点

　- 「Dockerfile」や「docker-compose.yml」はファイルとして作成する必要がある

## hands-onの実施

- 各種コマンドについて

1.__「docker compose up -d」__---コンテナの起動。

2.__「docker ps」__---実行中のコンテナのみを確認。後ろに　「-a」 or 「-all」をつけると全てを表示。

3.__「docker compose exec db mysql -uroot -p」__---rootユーザでMySQL(データベース)にログイン。-pの次に必ずパスワードを入れる。

4.__「show databases;」__---データベースの一覧を確認。

5.__「use movie_list;」__---useの後に該当のデータベースを選択するとDBを切り替える。

6.__「show tables;」__---テーブルの一覧を表示。

7.__「select * from movies;」__---moviesテーブルのレコードを確認。

8.__「insert into movies (name, director) values ("ゴッドファーザー", "フランシス・フォード・コッポラ");」__---values("name" , "director")を入れるとこれらをカラムに挿入。

9.__「select * from movies;」__---レコードの挿入結果を確認。

10.__「exit」__---MySQLからログアウト。

## hands-onの実施結果

<img width="762" alt="スクリーンショット 2023-01-15 21 38 59" src="https://user-images.githubusercontent.com/120763272/212542234-f70525a7-5599-45c9-9254-e584ced1f71f.png">


<img width="1093" alt="スクリーンショット 2023-01-15 17 39 17" src="https://user-images.githubusercontent.com/120763272/212542237-63acf5dd-22c1-4e89-b0d1-b91712ed8975.png">

