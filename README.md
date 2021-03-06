# 目的
- 『何』に『いくら』『どこから』支出したかが管理できる
- 家計簿や出納帳ではない

# ターゲット
- お小遣い管理をしたい男性

# 機能
## 入力する（InputScene）
- 起動したら即入力ができる
	- アプリが前面にきたら（起動・バックグラウンドから）入力画面を表示させる
	- キーボードも表示されていて、金額の入力ができる状態
- 入力項目
	- 金額（『いくら』にあたる部分）
	- 項目（『何』にあたる部分）
	- 出元（『どこから』にあたる部分。現金・カードなど）
	- ラベル（ラベルごとに支出を管理できる。１支出に１ラベル）
	- 日付（今日の日付を表示済み）

## 日々の支出を見る（ListScene）
- 入力した内容が日付単位で表示されている
- レコードをスライドすることで、編集・削除が可能
- 月単位にヘッダを上部に固定表示

## 月の支出の割合を見る（ProportionScene）
- 月単位でラベルごとの支出割合を確認する
- 右スワイプで前月／左スワイプで次月を表示
- 円グラフでラベル単位の割合を表示
- 円グラフの下にラベルごとの横線グラフ（金額表示）
- 横線グラフのタッチでラベルごとの月単位の支出一覧画面を表示

## 設定する（SettingScene）
- ラベルを登録・編集・削除する
- 出元を登録・編集・削除する