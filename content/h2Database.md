H2 Databaseに登録したデータを確認する
------------------------------------------

### 前提
- アプリケーションが起動していること

### 手順

1. H2データベースコンソールをブラウザで開く<br>
    - 以下のURLにアクセスをしてください。
        - http://localhost:9080/h2-console/

1. JDBC URL/User Name/Passwordを以下の通り入力し、「Connect」を押す。
    - JDBC URL : `jdbc:h2:file:./target/db/intern`
    - User Name : `sa`
    - Password : 　※Passwordは何も入力をしないで空欄にする。

1. 左側のペインのテーブル名をクリックすると、クリックしたテーブルに対するSELECT文が生成される。

1. [実行]ボタンをクリックすると、生成したSELECT文が実行され、テーブルのデータを確認することができる。
