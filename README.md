# DanpaSync ブラウザ プラグイン

DanpaSyncPro の中で Web ブラウザを起動して、ページの動画を待機映像にするプラグイン。

DJ・VJ 用ソフト DanpaSyncPro 向けの、無償のプラグインです。ご使用には DanpaSyncPro 本体が必要です。

> このプラグインは DanpaSyncPro の販売物には含まれない、別配布の無償・無保証のものです。

## できること

- DanpaSyncPro の中で Web ブラウザ（Safari と同じ WebKit）を起動して、好きなサイトを開けます。アドレスの欄には、URL（`https://` は省略できます）か検索したい言葉を入れます。
- 開いたページの動画を、DanpaSyncPro の待機映像（「一致しないときの映像」）として出力できます。
- ライブラリにない曲の場合、ShazamKit を使用し曲を特定して検索し、検索結果から選んだ動画の位置を曲に合わせます（自動で合わせるのは YouTube の動画だけです）。

## ダウンロード

**[⬇ ダウンロード（DanpaSyncOwnBrowser.dmg）](https://github.com/danpasync-plugins/danpasync-browser-plugin/releases/latest/download/DanpaSyncOwnBrowser.dmg)**

押すと、いちばん新しい版の dmg がそのままダウンロードされます。dmg は Apple の公証（notarization）済みです。
Releases のページに出る「Source code」は使いません（ダウンロードしなくてかまいません）。

| プラグイン | 約束事の版 | 使える DanpaSyncPro |
| --- | --- | --- |
| 0.3.1 | 4 | 0.1.1 以降 |
| 0.3.0 | 4 | 0.1.1 以降 |
| 0.2.0 | 4 | 0.1.1 以降 |
| 0.1.0 | 2 | 0.1.0 |

0.2.0 以降は DanpaSyncPro 0.1.1 以降が必要です（0.1.0 の DanpaSyncPro には読み込めません）。

## 動作環境

- DanpaSyncPro（上の表の版）
- Apple シリコンの Mac（M1 以降）、macOS 14 (Sonoma) 以降
- 曲の照会にインターネット接続（Apple の Shazam）を使います

## 使い方

1. ダウンロードした dmg を開く。
2. DanpaSyncPro を開き、「設定…」（⌘,）の「連携」タブで「プラグインを追加…」を押す。
3. dmg の中の `DanpaSyncOwnBrowser.bundle` を選んで「開く」。
4. DanpaSyncPro を終了して（⌘Q）、開き直す。
5. 本体の画面のデッキの上に「デッキ｜自前ブラウザ」のタブが出れば完了です。「自前ブラウザ」のタブでページを開き、「一致しないときの映像」で「自前ブラウザの映像」を選ぶと、ページの動画が待機映像になります。

手で入れる場合は、「プラグインのフォルダを開く」で開いたフォルダへ `DanpaSyncOwnBrowser.bundle` をドラッグして、DanpaSyncPro を開き直してください。

- Mac: `~/Library/Application Support/DanpaSync/Plugins`

## 更新・取り外し

- 更新: 新しい dmg で「使い方」をもう一度行うと入れ替わります（古いものはゴミ箱へ移ります）。
- 取り外し: DanpaSyncPro を終了してから、上のフォルダの `DanpaSyncOwnBrowser.bundle` をゴミ箱へ入れます。
- フォルダを開くときは、Finder の「移動」→「フォルダへ移動…」（⇧⌘G）に上のパスを貼り付けます。

## 読み込めないとき

「設定…」の「連携」タブに理由が出ます。

- 「プラグインが古い」: DanpaSyncPro の版に合うプラグインを、Releases から入れ直してください。
- 「本体が古い」: DanpaSyncPro を最新版に更新してください。
- 「署名が本体と合わない」: このページ以外から入手したものか、壊れています。Releases の dmg から入れ直してください。

## 注意

- 映像にできるのは、ページの中の動画です。ページ全体の画面は映りません。サイトによっては、動画を映像として取り出せないことがあります。
- 開いたサイトは、それぞれの利用規約に従ってお使いください。このプラグインは広告を飛ばしたり消したりしません。
- 動画を人前で映す（クラブやイベントで上映する）ときの権利の確認は、使う方の責任で行ってください。
- プラグインは DanpaSyncPro と同じ中で動きます。プラグインが原因で止まったときは、上の「取り外し」をしてから DanpaSyncPro を開けば、プラグインなしで使えます。
- 無償・無保証です。このプラグインについて、DanpaSyncPro の販売窓口ではお問い合わせを受け付けていません。
- YouTube は Google LLC の商標です。このプラグインは Google・YouTube とは関係ありません。
