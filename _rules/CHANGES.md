# 共通部分の変更の記録

新しい行を下に足す。各 OS の Claude は、`git pull` の後に前回から増えた行を読む。

| 日付 | 変更点 | もう一方の OS で必要な対応 |
|---|---|---|
| 2026-10-25 | 運用ルール v2 を作成。文書をアプリ×OS ごとに分け、URL を `apps/<アプリ名>/<OS>/` にした。共通ページからアプリ名と広告 SDK の具体的な説明を外した。`apps/picdule/` と `apps/picdule/privacy/` は OS を選ぶ案内ページにした。雛形 `_template/` と `.gitattributes` を追加 | Android：Picdule の `apps/picdule/android/` と `apps/picdule/android/privacy/` を、Android のリリースの前に雛形から作る。案内ページの「Android（準備中）」をリンクに変える（共通部分の変更なのでオーナーの承認を得る）。Play Console のプライバシーポリシー URL とウェブサイトを、`apps/picdule/android/privacy/` と `apps/picdule/android/` に1回で変える（オーナー）。燃費記録の `apps/nenpi/android/` も同様 |
