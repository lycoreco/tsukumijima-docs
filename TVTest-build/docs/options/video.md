# 映像

## デコーダ

各映像フォーマットのデコーダを選択します。  
「自動」を選択すると、利用可能なデコーダを検索して使用します。  
リストにあっても実際には使用できないものもあります。  
詳しくは[デコーダとレンダラ](../appendix/decoder.md)を参照してください。

## 映像レンダラ

映像レンダラを選択します。  
レンダラによって画質やパフォーマンスに影響を与えます。  
Vista 以降の場合は EVR がいいと思います(ただしキャプチャの画質に問題あり)。  
詳しくは[デコーダとレンダラ](../appendix/decoder.md)を参照してください。

## 番組切り替わり時にパン&スキャンをデフォルトに戻す

番組が切り替わった際に、パン&スキャンの設定をデフォルトに戻すようにします。  
このチェックをしていない場合でも、チャンネルを切り替えた際は必ずデフォルトに戻ります。

## サイドカット時に両端をマスクしない

サイドカット時にカットした領域をマスクせずにそのまま表示します。  
チェックをしないとカットした領域が黒くマスクされます。

## 全画面表示時にディスプレイに合わせて切り抜いて表示する

## 最大化時に画面の大きさに合わせて切り抜いて表示する

全画面表示/最大化時に、映像の端をカットして画面全体で表示するようにします。  
例えば、16:9 の映像を 4:3
のモニタで見る場合、チェックをしないと上下に黒帯がついた状態で表示されますが、チェックをすると左右がカットされて黒帯のない状態で表示されるようになります。

## 拡張ヘッダのディスプレイサイズを無視する

MPEG-2 拡張ヘッダのディスプレイ拡張で指定されているサイズを無視するようにします。  
パン&スキャンをデフォルトにした際に余計に切り抜かれる場合に指定してください。

## 複数モニタにまたがる時クリップする (EVR)

EVR 使用時、映像が複数モニタにまたがる場合に、最も多く重なるモニタでクリップします。  
これは EVR のデフォルト動作です。

