# DanpaSync ブラウザ プラグイン

DanpaSyncPro に読み込ませて使う、無償のプラグインです。
DanpaSyncPro の画面に「自前ブラウザ」のタブを足し、会場で流れている曲の検索ページを開きます。選んだ動画の再生位置を、会場の曲に自動で合わせます。合わせた映像は、DanpaSyncPro の待機映像として出力できます。

> このプラグインだけでは動きません。先に DanpaSyncPro を入れておいてください。
> このプラグインは DanpaSyncPro の販売物には含まれない、別配布の無償・無保証のものです。

## ダウンロード

[Releases](../../releases/latest) から、最新の `DanpaSyncOwnBrowser-….dmg` をダウンロードしてください。
dmg は Apple の公証（notarization）済みです。

| プラグイン | 約束事の版 | 使える DanpaSyncPro |
| --- | --- | --- |
| 0.2.0 | 4 | 0.1.1 以降 |
| 0.1.0 | 2 | 0.1.0 |

0.2.0 は DanpaSyncPro 0.1.1 以降が必要です（0.1.0 の DanpaSyncPro には読み込めません）。本体とプラグインを両方更新してください。

## 動作環境

- DanpaSyncPro（上の表の版）
- Apple シリコンの Mac（M1 以降）、macOS 14 (Sonoma) 以降
- 曲の照会にインターネット接続（Apple の Shazam）を使います

## 入れ方

1. ダウンロードした dmg を開く。
2. DanpaSyncPro を開き、「設定…」（⌘,）の「連携」タブで「プラグインを追加…」を押す。
3. dmg の中の `DanpaSyncOwnBrowser.bundle` を選んで「開く」。
4. DanpaSyncPro を終了して（⌘Q）、開き直す。
5. 「連携」タブの「プラグイン」に設定が出れば完了です。本体の画面のデッキの上に「デッキ｜自前ブラウザ」のタブが出ます。

手で入れる場合は、「プラグインのフォルダを開く」で開いたフォルダへ `DanpaSyncOwnBrowser.bundle` をドラッグして、DanpaSyncPro を開き直してください。

## 更新・取り外し

- 更新: 新しい dmg で「入れ方」をもう一度行うと入れ替わります（古いものはゴミ箱へ移ります）。
- 取り外し: DanpaSyncPro を終了してから、「プラグインのフォルダを開く」で開いたフォルダの `DanpaSyncOwnBrowser.bundle` をゴミ箱へ入れます。
- DanpaSyncPro が開けないときは、Finder の「移動」→「フォルダへ移動…」（⇧⌘G）に `~/Library/Application Support/DanpaSync/Plugins` を貼り付けて開きます。

## 読み込めないとき

「設定…」の「連携」タブに理由が出ます。

- 「プラグインが古い」: DanpaSyncPro の版に合うプラグインを、Releases から入れ直してください。
- 「本体が古い」: DanpaSyncPro を最新版に更新してください。
- 「署名が本体と合わない」: このページ以外から入手したものか、壊れています。Releases の dmg から入れ直してください。

## ご注意

- 動画サイトは、それぞれの利用規約に従ってお使いください。このプラグインは広告を飛ばしたり消したりしません。
- 動画を人前で映す（クラブやイベントで上映する）ときの権利の確認は、使う方の責任で行ってください。
- プラグインは DanpaSyncPro と同じ中で動きます。プラグインが原因で止まったときは、上の「取り外し」をしてから DanpaSyncPro を開けば、プラグインなしで使えます。
- 無償・無保証です。このプラグインについて、DanpaSyncPro の販売窓口ではお問い合わせを受け付けていません。
- YouTube は Google LLC の商標です。このプラグインは Google・YouTube とは関係ありません。
