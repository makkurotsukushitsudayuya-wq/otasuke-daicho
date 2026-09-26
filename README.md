# お助けボット 台帳(入力画面・管理者アプリ)

お助けボットのFAQ台帳を入力・管理する画面。GitHub Pagesで公開している。
データはGoogle Apps Script(`gas-projects/qa-bot`)経由でスプレッドシート「お助けボット台帳」に保存される。
このページ自体にはデータを含まず、合言葉がないと台帳は読み書きできない。

| 公開URL | 中身 | 元のファイル |
|---|---|---|
| `/otasuke-daicho/` | スタッフ用の入力画面(質問をすばやく追加) | `qa-bot/editor.html` |
| `/otasuke-daicho/admin/` | 管理者アプリ(その場編集・絞り込み・まとめて変更/削除・店舗と記入者のリスト) | `qa-bot/admin.html` |

画面を直すときは qa-bot 側を直してから、ここの `index.html` / `admin/index.html` にコピーする。
