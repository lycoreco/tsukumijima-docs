# チャンネルファイル

チャンネルファイルは、チャンネルの設定が保存されているファイルです。  

TVTest ver.0.8.0 から、cap_hdus などと互換性のあるチャンネルファイル(*.ch)は使用できなくなりました。

## チャンネルファイルの優先度

[チャンネルスキャン](../options/channelscan.md)を行うと、BonDriver と同じベース名の *.ch2
ファイルが作成されます。このファイルが存在する場合、TVTest はこのファイルからチャンネル設定を読み込みます。  
チャンネルファイルが存在しない場合は、BonDriver の対応している全てのチャンネルから選択するようになります。
