- このフォルダ内部の CSS をプレビューに反映するためには

1. css をコピー 拡張子を less に変更
2. 適用したい md ファイル内に@import "../css/default.less"等で表示可能

- 別の方法として以下も使えるがローカルの物しか変わらないので汎用性は無くなる
  ファイルごとに見た目を変える事もできない

1. css をコピー
2. ctrl + shift + P でパレットを開く
3. markdown-preview-enhanced: Customize CSS を選択
4. style.less 内部の markdown-preview-enhanced クラスの CSS を書き換える
