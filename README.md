# line-bot_health

gas(google apps script)を使ったアプリです。LINEから使えるアプリで、主に以下のことができます。
- 体重の入力(複数回入力した場合は最新のものが記録されます)
- 体重の確認(今日の体重、昨日の体重、週単位や月単位などの統計情報)
- 食事の入力(PFC、よく食べるものはデフォルトにして入力を簡単にしています)
- 食事の確認(今日のPFC、昨日のPFC、週単位や月単位などの統計情報)
- Slisimという、食事名からカロリーを計算できるアプリを開けるようにしています。
- 体重のリセット、食事のリセット(全てのデータをリセットする)
体重データや食事データは[スプレッドシート](https://docs.google.com/spreadsheets/d/1HIIa2pAwfRJ6N3ImC2MEfVSNWZL6hiPCo8QCCbvgPU0/edit?usp=sharing)に保存しています。つまり、スプレッドシートをデータベースのように使っています。コードを見るには[ツール]->[スクリプトエディタ]と進んでください。ここでは、UIを定義しています。


その他に以下のスプレッドシートを作成しました。スプレッドシートには何も記録していませんが、コードを管理しやすくするために用意しました。先ほどと同様にして[ツール]->[スクリプトエディタ]と進んでください。
- 体重入力をする前後の操作は[このスクリプト](https://docs.google.com/spreadsheets/d/1FcUqcl-xWIi5fkYVbcc_wIZsuCjJUaQxvBDHhlyj7iI/edit?usp=sharing)によって行われます。
- 体重確認をする前後の操作は[このスクリプト](https://docs.google.com/spreadsheets/d/1cfLsRrtQYFRRhsWDRvmn4gzEIOuM02I74iAzKfNIw5c/edit?usp=sharing)によって行われます。
- 体重リセットをする操作は[このスクリプト](https://docs.google.com/spreadsheets/d/1i9rIeT7oMS_QQsnSL3UbCcCfa7YdDYGjMGXWSVwlCo0/edit?usp=sharing)によって行われます。
- 食事入力をする前後の操作は[このスクリプト](https://docs.google.com/spreadsheets/d/1FcUqcl-xWIi5fkYVbcc_wIZsuCjJUaQxvBDHhlyj7iI/edit?usp=sharing)によって行われます。
- 食事確認をする前後の操作は[このスクリプト](https://docs.google.com/spreadsheets/d/1i77mTMTzCfChaibQW0gWUAxluntmqKDVBqYJb4fYgCg/edit?usp=sharing)によって行われます。
- 食事リセットをする操作は[このスクリプト](https://docs.google.com/spreadsheets/d/1HIIa2pAwfRJ6N3ImC2MEfVSNWZL6hiPCo8QCCbvgPU0/edit?usp=sharing)によって行われます。


