# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
* リモートリポジトリ
* ネット上に配置して複数人で共有するためのリポジトリ
* ローカルリポジトリ
* 開発者一人ひとりが使用するために自分のPC上に配置するためのリポジトリ


## プッシュとマージの違いは何でしょうか？
* プッシュがリモートリポジトリにローカルリポジトリの内容、履歴を更新する
* マージが分岐させたブランチを現在のブランチに統合させる


## コミットとプッシュの違い
* コミットはローカルリポジトリで変更履歴を保存することでプッシュが変更履歴をリモートリポジトリに反映、更新させること


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
* コミットメッセージを確認すれば、どのような変更を行ったか分かるように簡潔に書く


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
* ローカルでマージしてしまうとバグがあった際にブランチごとの差分を確認できないまま反映せてしまうがプルリクエストを行うことでリモート上でコードレビューをしてもらいマージすることができるので事前にバグも防ぐことができ、コードの品質向上にも繋がる


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
* 自分以外の人が書いたソースコードの内容を把握する必要があるため、少しでも意図が読み取れない処理とぶつかってしまった場合は、そのソースコードを書いた人と相談しながら作業を進めて
* 先にマージされた変更内容を取り込む
* 後にマージしようとしている変更内容を取り込む
* どちらの変更内容も取り込む
３つのうちどれかの方法で変更内容を取り込む