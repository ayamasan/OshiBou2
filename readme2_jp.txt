M5StickCとLEDテープ(29LED品)を使って空中に文字を表示できます。
iPhoneアプリ(OshiBou2)で作成した文字データをM5StickCに転送して使用します。
M5StickCの表示データ作成と転送は、iPhoneアプリOshiBou2を使用します。

特徴
- 設定した文字列をLEDテープで表示可能
- データはWi-Fi経由で直接M5Stickに転送
- 表示は、1文字毎か全文字
- 表示開始は、Aボタンか振る動作
- 表示方向は、左右交互か片方向のみ
- 表示速度は2段階
- 文字色は7色から選択可能
- 背景に黒と白を設定可能

プログラムの書き込み方
1. Windowsのに新しいフォルダを作成しoshibou2.ino.m5stick_c.zipをコピーする
2. oshibou2.ino.m5stick_c.zipを解凍する
3. WindwosPCにM5StickCをUSB接続して、接続されたCOMポート番号をチェック
4. ESP32Write.batを実行し、COMポート番号を入力する
5. リターンキーを押すと書込を実行する

使い方
1. M5stickCにWi-Fiのパスワードを設定（初回のみ）
2. Aボタン5秒押しでデータ転送待ち状態にする
3. iPhoneをM5stickCアクセスポイントへ接続
4. iPhoneアプリ(OshiBou2)で文字入力をしてフォント作成を押す
5. アプリの送信ボタンでM5stickCにデータ転送する
