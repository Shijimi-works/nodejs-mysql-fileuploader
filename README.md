# nodejs-mysql-fileuploader

YOUTUBE（https://youtu.be/qU2-vnx0t8s）参考
画像投稿アプリケーションの作成
（Node.jsとMysqlを使用）

・技術スタック（言語、フレームワーク、ライブラリ、ツールの組み合わせのこと）
クライアント（HTMLのみ）、サーバー（node.js、express）、データベース（MYSQL、XAMPP （MYSQLのアパッチとして使用））を使用

（主な流れ）
クライアントからWeb上で画像を送信⇩
サーバーサイド側で設定したAPIがMYSQLへ画像を保存⇩
保存したもをサーバーに戻して、クライアント側（Web上）へ表示する
