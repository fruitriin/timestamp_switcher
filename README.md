# Twitter Timestamp Switcher for Chrome

Twitter公式WebのTLで相対時間表記（n秒前、n分前）を絶対時間表記(hh:mm:ss)に直すChrome拡張機能です。
違う日・年のツイートには[YYYY/]MM/DDがつきます。

## つかいかた
1. `chrome://extentions`
2. 「デベロッパーモードを有効にする」にチェック
3. 「パッケージ化されていない拡張機能を読み込む…」からこの中身がまるごと入ったディレクトリを選択

## おことわり
1秒毎に表記を変換する関数を回しているので、新しいツイートを読み込んでからほんの一瞬だけ相対時間に戻ってしまうことがありますがご了承ください。
