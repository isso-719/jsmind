# TODO

1. Sinatra に導入する

2. サーバ側に upload_data() の POST 先を用意して、それを erb に適用する

3. open_file() などにコメントアウトされている `// upload_data();` のコメントを外す

4. `// Web サイトを読み込んだときに実行する` の後の処理を変更する
4.1 具体的にはデータベースから呼び出して、データがあればそのデータを呼び出す。
4.2 なければ `open_empty();` を実行する