# Node-RED PCON-EIP動作フロー

## 概要
本フローはNode-REDとIAI社PCON(Ethernet/IP)を通信・動作させるためのフロー（json）です。

## 追加ノード
・パレットの管理 → ノードの追加　より追加  
node-red-contrib-buffer-parser  
node-red-contrib-ui-led  

・npm installより追加  
@serafintech/node-red-contrib-eip-io  
※docker上のNode-REDへインストールする場合は下記参考にしてください。  
https://fabulous-industry.com/?p=463

## フローの読み込み
読み込み  
![image](https://github.com/user-attachments/assets/537cf1de-c088-4461-b26c-130d62be1f5e)  

ダウンロードしたflow.jsonを貼り付けor読み込み  
![image](https://github.com/user-attachments/assets/3c201d35-364e-4a3a-9406-d8a5f1939841)


