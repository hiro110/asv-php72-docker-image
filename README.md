# Docker image test for Web App for Containers
App Service on Linuxのカスタマイズイメージサンプル  
変更点は次の通り  

* タイムゾーン変更
* apacheのアクセス、エラーログ出力設定
* apacheのレスポンスヘッダ設定
* gzip設定

元イメージはここからfork  
https://github.com/Azure-App-Service/php/tree/master/7.2.11-apache