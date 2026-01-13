葉酸KW完成版 - Squadbeyond用ウィジェット分割テンプレート
========================================================

このフォルダには、切り替えボタンの仕組みのテンプレートが含まれています。
LP内容は各ファイルの指定された場所にコピペしてください。

【配置順序】
1. widget1_ボタン.html   - 切り替えボタン + CSS + JavaScript（必ず最初に配置）
2. widget2_mitas.html    - 妊活中（mitas）コンテンツ
3. widget3_mamaru.html   - 妊娠中（mamaru）コンテンツ

【LP内容の貼り付け方】
1. widget2_mitas.html を開く
2. 「↓↓↓ ここから妊活中（mitas）のLP内容を貼り付け ↓↓↓」と
   「↑↑↑ ここまで妊活中（mitas）のLP内容 ↑↑↑」の間に
   妊活中のLP内容（HTML/CSS）をコピペする

3. widget3_mamaru.html を開く
4. 「↓↓↓ ここから妊娠中（mamaru）のLP内容を貼り付け ↓↓↓」と
   「↑↑↑ ここまで妊娠中（mamaru）のLP内容 ↑↑↑」の間に
   妊娠中のLP内容（HTML/CSS）をコピペする

【仕組み】
- JavaScriptが document.querySelectorAll を使用してページ全体から
  data-tab-trigger と data-tab-content 属性を持つ要素を検索します
- そのため、別々のウィジェットに分かれていても、同じページ内であれば
  切り替えボタンが正常に動作します

【注意事項】
- widget1_ボタン.html は必ず最初に配置してください（JavaScriptが含まれているため）
- 3つのウィジェットは同じページ内に配置する必要があります
- 初期表示は「妊活中（mitas）」になります
- LP内容をコピペする際、コメント行（<!-- -->）は削除しないでください
