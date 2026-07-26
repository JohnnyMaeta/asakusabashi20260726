# 第3回 先生の学校　公立の教室で起きている AIの授業
## 2026年7月26日（日）9:30〜12:00｜東京国際ビジネスカレッジ 2号館（東京都台東区柳橋2-7-5）

主催：内閣府認定 公益財団法人 こども教育支援財団「先生の学校」
講師：前多昌顕（青森県五所川原市立五所川原小学校）／モデレーター：二川佳祐

- 指導要領PDFの読み込みと授業プラン生成
- 評価基準（ルーブリック）作成
- 前半の指導案をAI指示文に活用
- 評価基準のGoogleフォーム変換
- スーパー記録くん導入
- Google Workspace Studioの活用

---

## 🛠️ ワークショップ・ツール

### 1. メインツール

- <a href="https://gemini.google.com/" target="_blank">Gemini (Google AI)</a>
- <a href="https://notebooklm.google.com/" target="_blank">Gemini Notebook</a>
- <a href="https://script.google.com/macros/s/AKfycbx9ckesaH03gAdnhxVDtIAZHbSB_7l2RPGNuJ2EQ6AgahELB9wsu03nAboq8yFrEnSgNw/exec" target="_blank">スーパー記録くん</a>
- <a href="https://studio.workspace.google.com/" target="_blank">Google Workspace Studio</a>
- <a href="https://script.google.com/macros/s/AKfycbyiV2IEOdW90UFjD3J4MM6XR8FZfJU65Q877ry_xmv8FDhiLVnKMU7STT_kIicQEMQxMQ/exec" target="_blank">アカウント貸与ページ</a>


### 2. 資料・リソース

#### 📄 研修共通資料・リンク
-  <a href="https://www.mext.go.jp/a_menu/shotou/new-cs/1387014.htm" target="_blank">小学校学習指導要領</a>
-  <a href="https://www.mext.go.jp/a_menu/shotou/new-cs/1387016.htm" target="_blank">中学校学習指導要領</a>
-  <a href="https://www.mext.go.jp/a_menu/shotou/seitoshidou/1404008_00001.htm" target="_blank">生徒指導提要</a>
-  <a href="https://docs.google.com/document/d/1mCnWumizHGcCY5EIYgMHwa-EptVDhL3FtnKrNJGs9NM/edit?usp=sharing" target="_blank">プロンプト等</a>
-  <a href="https://docs.google.com/document/d/156iIMF5XUiledLLkdtpFPN7T6wpj6dA0xwd6NGbsN_0/edit?usp=sharing" target="_blank">本日の要約ファイル</a>
-  <a href="https://www.amazon.co.jp/stores/%E5%89%8D%E5%A4%9A-%E6%98%8C%E9%A1%95/author/B09RGNX3XZ?ref=sr_ntt_srch_lnk_1&qid=1783488335&sr=8-1&shoppingPortalEnabled=true" target="_blank">前多昌顕の著書一覧（Amazon著者ページ）</a>
-  <a href="./振り返りdemo1.png" target="_blank">振り返りdemo1（手書き振り返りサンプル画像）</a>
-  <a href="./振り返りdemo2.png" target="_blank">振り返りdemo2（手書き振り返りサンプル画像）</a>
-  <a href="./振り返りdemo3.png" target="_blank">振り返りdemo3（手書き振り返りサンプル画像）</a>

#### ✍️ 演習用テキスト資料
架空の自治体・学校の公式サイト風ページです。ページ内の「📋 本文をコピー」ボタンでテキストをそのままコピーできます（Markdown原文も併記）。

-  <a href="./戯画市の教育方針.html" target="_blank">戯画市の教育方針（演習用・架空の資料）</a>　<small><a href="./戯画市の教育方針.md" target="_blank">[Markdown原文]</a></small>
-  <a href="./戯画市立戯画小学校_学校経営方針.html" target="_blank">戯画市立戯画小学校 学校経営方針（演習用・架空の資料）</a>　<small><a href="./戯画市立戯画小学校_学校経営方針.md" target="_blank">[Markdown原文]</a></small>
-  <a href="./穴炉愚市の教育方針.html" target="_blank">穴炉愚市の教育方針（演習用・架空の資料）</a>　<small><a href="./穴炉愚市の教育方針.md" target="_blank">[Markdown原文]</a></small>
-  <a href="./穴炉愚市立穴炉愚小学校_学校経営方針.html" target="_blank">穴炉愚市立穴炉愚小学校 学校経営方針（演習用・架空の資料）</a>　<small><a href="./穴炉愚市立穴炉愚小学校_学校経営方針.md" target="_blank">[Markdown原文]</a></small>
-  <a href="./魁市の教育方針.html" target="_blank">魁市の教育方針（演習用・架空の資料）</a>　<small><a href="./魁市の教育方針.md" target="_blank">[Markdown原文]</a></small>
-  <a href="./魁市立魁小学校_学校経営方針.html" target="_blank">魁市立魁小学校 学校経営方針（演習用・架空の資料）</a>　<small><a href="./魁市立魁小学校_学校経営方針.md" target="_blank">[Markdown原文]</a></small>
-  <a href="./擬野流市の教育方針.html" target="_blank">擬野流市の教育方針（演習用・架空の資料）</a>　<small><a href="./擬野流市の教育方針.md" target="_blank">[Markdown原文]</a></small>
-  <a href="./擬野流市立擬野流小学校_学校経営方針.html" target="_blank">擬野流市立擬野流小学校 学校経営方針（演習用・架空の資料）</a>　<small><a href="./擬野流市立擬野流小学校_学校経営方針.md" target="_blank">[Markdown原文]</a></small>
-  <a href="./筋肉市の教育方針.html" target="_blank">筋肉市の教育方針（演習用・架空の資料）</a>　<small><a href="./筋肉市の教育方針.md" target="_blank">[Markdown原文]</a></small>
-  <a href="./筋肉市立筋肉小学校_学校経営方針.html" target="_blank">筋肉市立筋肉小学校 学校経営方針（演習用・架空の資料）</a>　<small><a href="./筋肉市立筋肉小学校_学校経営方針.md" target="_blank">[Markdown原文]</a></small>

#### 📺 解説動画

-  <a href="https://youtu.be/9XHhJMjaMog" target="_blank">【動画】指導案・評価の爆速作成（YouTube）<br><img src="https://img.youtube.com/vi/9XHhJMjaMog/mqdefault.jpg" alt="【動画】指導案・評価の爆速作成" width="320" style="margin-top: 5px; border-radius: 4px;"></a>
-  <a href="https://youtu.be/eNU-hdRT15k" target="_blank">【動画】評価基準のGoogleフォーム変換（YouTube）<br><img src="https://img.youtube.com/vi/eNU-hdRT15k/mqdefault.jpg" alt="【動画】評価基準のGoogleフォーム変換" width="320" style="margin-top: 5px; border-radius: 4px;"></a>
-  <a href="https://youtu.be/8sZS3oCD6t4" target="_blank">【動画】Google Workspace Studioでフォームを自動分析（YouTube）<br><img src="https://img.youtube.com/vi/8sZS3oCD6t4/mqdefault.jpg" alt="【動画】Google Workspace Studioでフォームを自動分析" width="320" style="margin-top: 5px; border-radius: 4px;"></a>
-  <a href="https://youtu.be/kbwSA1hWskw" target="_blank">【動画】毎日の振り返り分析を完全自動化！Geminiとドキュメントを繋ぐ5ステップ（YouTube）<br><img src="https://img.youtube.com/vi/kbwSA1hWskw/mqdefault.jpg" alt="【動画】毎日の振り返り分析を完全自動化！Geminiとドキュメントを繋ぐ5ステップ" width="320" style="margin-top: 5px; border-radius: 4px;"></a>
-  <a href="https://youtu.be/_vmQsKdcidk" target="_blank">【動画】初めてでも3分でできる！手書きの振り返り画像を自動でスプレッドシートにデータ集計するフロー（YouTube）<br><img src="https://img.youtube.com/vi/_vmQsKdcidk/mqdefault.jpg" alt="【動画】初めてでも3分でできる！手書きの振り返り画像を自動でスプレッドシートにデータ集計するフロー" width="320" style="margin-top: 5px; border-radius: 4px;"></a>
-  <a href="https://youtu.be/GDBY-kfT0ZI" target="_blank">【動画】マイク制限を完全突破！完全にGASだけで動く「スーパー記録くんネオ2」導入手順（YouTube）<br><img src="https://img.youtube.com/vi/GDBY-kfT0ZI/mqdefault.jpg" alt="【動画】マイク制限を完全突破！完全にGASだけで動く「スーパー記録くんネオ2」導入手順" width="320" style="margin-top: 5px; border-radius: 4px;"></a>
-  <a href="https://youtu.be/c8GpmkdXHCU" target="_blank">【動画】Googleの仕様変更に対応！子どもたちの声を集められるスーパー記録くん neo（YouTube）<br><img src="https://img.youtube.com/vi/c8GpmkdXHCU/mqdefault.jpg" alt="【動画】Googleの仕様変更に対応！子どもたちの声を集められるスーパー記録くん neo" width="320" style="margin-top: 5px; border-radius: 4px;"></a>
