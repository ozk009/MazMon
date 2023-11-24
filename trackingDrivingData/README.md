# 概要
Androidで動作するNode-RED環境、[RedMobile](https://play.google.com/store/apps/details?id=com.okhiroyuki.redmobile&hl=ja)で動作するGPSトラッカーです。
取得したデータはIoTプラットフォームSORACOMに送り、データを保存します。
*※スマートフォンには[SORACOMのSIM](https://soracom.jp/services/air/cellular/)を挿入して使う必要があります。*

# 使い方
開始、終了、リセットは同一のスマートフォンのWebブラウザから、JavaScriptで以下のAPIリクエストで実行します。
http://127.0.0.1:1880/api/start?id=${id}
http://127.0.0.1:1880/api/stop
http://127.0.0.1:1880/api/reset
