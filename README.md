# edamameBot

## edamameBotとは？

edamammeBotとは、部活で利用しているSlack上で動いているBOTです。  
hubotをRaspberryPi上で動かしています。

### スクリプト一覧

__スクリプトを追加、変更した場合、ここに追記願します。__


1. edamame  
テスト用のスクリプトです。  
お試ししたい機能がある時は、このスクリプトに追加して試します。  
ネタ・１発のなんかもここに。
2. blog  
ブログの更新順を決定するための機能です。  
チャンネルのメンバー情報をAPIを叩いて取得して、その中から1人選んでいます。  
3. clubroom  
部室の入退室管理用のための機能です。  
Linuxコマンドを叩いて写真を撮影。  
それをpython+openCV+Pillowで加工して顔に笑い男マークを合成。  
それをAPIを叩いてSlackに投稿しています。  
4. temp  
CPUの温度を知るための機能です。  
5. laugh_man  
clubroomの笑い男版です。写真を撮った後、人の顔を笑い男に加工します。  
6. limit_read_only  
read_only(#general)の発言に@channelをつけないと、赤城さんに怒られる。  
