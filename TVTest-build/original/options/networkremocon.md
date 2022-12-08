# ネットワークリモコン

ネットワークリモコン機能を使用すると、EpgDataCap_Bon から呼び出して使用した際に、TVTest からチャンネルの変更ができるようになります。

## ネットワークリモコン機能を利用する

ネットワークリモコン機能を有効にします。コマンドラインの /nr でも可です。

## IPアドレス

リモコンの送信先のIPアドレスです。  
127.0.0.1 のように指定します。

## ポート番号

リモコンの送信先のポート番号です。  
EpgDataCap_Bon と設定を合わせてください。

## チャンネルファイル

EpgDataCap_Bon のチャンネルファイルを指定します。  
空欄にすると、自動的にチャンネルファイルを検索して使用しますので、通常は指定する必要はありません。  
チャンネルファイルを明示的に指定したい場合は、ファイル名を入力します。フォルダ名を省略すると、My Documents\EpgTimerBon
にあると仮定します。  
ここで選択したチャンネルファイルに対応した BonDriver のチャンネル設定ファイル(*.ch2 及び
*.ch)が存在する場合、そこからリモコン番号の設定を読み込みます。  
例えば、"BonDriver_HDUS(HDUS).ChSet.txt" ファイルが選択されている場合、"BonDriver_HDUS.ch2"
ファイルが存在すれば、そこから設定を読み込みます。
