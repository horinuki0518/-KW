葉酸KW完成版 - Squadbeyond用ウィジェット分割版
================================================

このフォルダには、葉酸KW完成版を3つのウィジェットに分割したファイルが含まれています。
Squadbeyondの文字数制限を回避するため、以下の順番で各ウィジェットを配置してください。

【配置順序】
1. widget1_ボタン.html   - 切り替えボタン + CSS + JavaScript（必ず最初に配置）
2. widget2_mitas.html    - 妊活中（mitas）コンテンツ
3. widget3_mamaru.html   - 妊娠中（mamaru）コンテンツ

【仕組み】
- JavaScriptが document.querySelectorAll を使用してページ全体から
  data-tab-trigger と data-tab-content 属性を持つ要素を検索します
- そのため、別々のウィジェットに分かれていても、同じページ内であれば
  切り替えボタンが正常に動作します

【注意事項】
- widget1_ボタン.html は必ず最初に配置してください（JavaScriptが含まれているため）
- 3つのウィジェットは同じページ内に配置する必要があります
- 初期表示は「妊活中（mitas）」になります
