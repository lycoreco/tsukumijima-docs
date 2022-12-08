# EPG番組表の検索

番組表の右クリックメニューから [番組の検索] を選択すると、キーワードなどを指定して番組の検索が行えます。  
キーワードのアルファベットの半角と全角は同一視されます。[大/小文字区別] のチェックが入っていなければ、大文字と小文字も同一視されます。  

## キーワード検索

キーワードは半角スペースで区切って複数指定することができ、その場合は全てのキーワードに一致する番組が検索されます。  
キーワードを | で区切ると、いずれかに一致する番組が検索されます。  
半角スペースを含むキーワードを指定する場合は " で囲います。  
キーワードの前に - を付けると、そのキーワードを含む番組が検索結果から除外されます。

|||
|---|---|  
検索例 ドラマ 殺人| "ドラマ" と "殺人" の両方を含む番組
ニュース | スポーツ| "ニュース" と "スポーツ" のいずれか又は両方を含む番組  
中継 巨人 | 阪神| "中継" を含んで、かつ "巨人" と "阪神" のいずれか又は両方も含む番組  
徹子 -部屋| "徹子" を含んで "部屋" を含まない番組  
  
## 正規表現検索

[正規表現] にチェックを入れると、正規表現を使用した検索が行えます。  
以下の2つのいずれかの正規表現エンジンが使用できます。  

### ECMAScript(JavaScript)互換

ECMAScript(JavaScript)と互換性のある正規表現です。こちらがデフォルトになっています。  
詳しくは JavaScript の正規表現の解説を参照してください。  
<https://developer.mozilla.org/ja/docs/Web/JavaScript/Guide/Regular_Expressions>

### bregonig.dll

K.Takata 氏によって開発されている Perl 互換の正規表現ライブラリです。ver.2 以降に対応しています。  
bregonig.dll をプログラムと同じフォルダに入れると利用できます。  
<http://homepage3.nifty.com/k-takata/mysoft/bregonig.md>

## ジャンル検索

ツリーの中から検索結果に含めたいジャンルをチェックします。  
大ジャンルがチェックされていて、その小ジャンルがいずれもチェックされていない場合、大ジャンルに該当する全ての番組が検索されます。  
