# Lounge

## サイト概要
ゲームの進捗を共有するメンバーでいいねしたり、コメントすることによって交流を深める

### サイトテーマ
ゲームの進捗を共有するサイト

### テーマを選んだ理由
友人とサンドボックス型（プレイヤーが自分なりに目的や目標を決めて遊んでいくゲームデザインである）オンラインゲームをしているときに、チャットを通して現在の進捗状況を確認することがあるが、
ゲームを終えるとログがなくなってしまう。そのためゲームをする仲間と何かログを残せたらいいなと思ったから。

### ターゲットユーザー
サンドボックス型ゲームをする人（マインクラフトだけで月間アクティブ1億3000万人、ほかのサンドボックス型ゲームを含めるともっと多いことが予想できる。）

### 主な利用シーン
ゲームをプレイする時

### アピールポイント
サンドボックス型ゲームで避けて通れないのは荒らしの対策である
荒らしとはオンライン上で知り合った仲間が嫌がらせで環境を破壊すること
この荒らしを防ぐために以下の機能を設ける

・権限ステータス<br>
権限ステータスというものには訪問者・参加者・副管理者・管理者があり、<br>
グループ内のメンバーを、それぞれの権限ステータスで分けることによって使える機能の詳細な設定が可能<br>
・投票機能<br>
グループでトークしてその人が相応しいかを判断し、投票する

グループへの参加を承認制にして、参加の許可をグループ内のメンバー間で投票をして決めたり、<br>
グループ内でアンケートを取りたい時などに使用<br>

## 設計書

機能一覧<br>
https://docs.google.com/document/d/1srmZzmJuJY8ALd_QHt6h4f0alffnHc8tzuU9vYmL7f8/edit

UI Flow<br>
Admin<br>
https://app.diagrams.net/#G1DzFO-KRQDamK4XiwZ-djKcXvm45zNGcb<br>
SubAdmin<br>
https://app.diagrams.net/#G1khABAp4GDptvbAJAt4q2ZOh4soxTGmeL<br>
Player<br>
https://app.diagrams.net/#G1zvr4dJ72qNDHQP_QMlTmYgRKepDkVyQH<br>
Visitor<br>
https://app.diagrams.net/#G1LrsTxtTensJiImOBhs22zwZk3cz08oUw

ワイヤーフレーム<br>
Admin<br>
https://drive.google.com/drive/folders/1wV9SwIPhSA8-u30HqewOb9JPOHnawMuI?ths=true<br>
Player<br>
https://drive.google.com/drive/folders/1JW80MQEC7St9ooENBn9zwM-Z5zoHw5p8?ths=true

ER図<br>
https://app.diagrams.net/#G1C-ap5HNuZJjrJ-QE4ma0wBUtT7p4XfVs

テーブル定義書<br>
https://docs.google.com/spreadsheets/d/1TfjXwK2kR8k9-E1dUABua5ycTvIgMIPMI-PlJM_BPXg/edit?usp=sharing

アプリケーション詳細設計<br>
https://docs.google.com/spreadsheets/d/14oYBkEOl9W4yaajskupbSsik5oF5FD3gj6d_JpRwjAY/edit?usp=sharing

## チャレンジ要素一覧
https://docs.google.com/spreadsheets/d/1ZBkKfYRC9YsImpBLNyuErKkjNPmAQs1Uw5L103a1YOU/edit?usp=sharing

## 開発環境
- OS：Linux(CentOS)
- 言語：HTML,CSS,JavaScript,Ruby,SQL
- フレームワーク：Ruby on Rails
- JSライブラリ：jQuery
- IDE：Cloud9

## 使用素材
- 外部サービスの画像素材・音声素材を使用した場合は、必ずサービス名とURLを明記してください。
- 使用しない場合は、使用素材の項目をREADMEから削除してください。
