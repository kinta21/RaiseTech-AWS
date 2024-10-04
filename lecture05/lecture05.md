# 第5回課題
## 組み込みサーバーでのRailsアプリケーションの動作確認
![組み込みサーバーでRails App動作確認](lecture05-img/running_rails_app_on_puma.png)  

## リッスン設定を Unix Socket に変更しcurlで動作確認
![UnixSocketを使ったPumaの動作確認](lecture05-img/puma_on_unix_socket_verify_with_curl.png)  

## Nginxの単体動作確認
![Nginxの単体動作確認](lecture05-img/nginx_standalone.png)  

## NginxとPumaでUnix socketを使った連携動作確認
![NginxとPumaでUnixSocketを使った連携動作確認](lecture05-img/nginx_puma_unix_socket_integration.png)  

## ALBを追加して動作確認
![ALBを追加して動作確認](lecture05-img/alb.png)

## S3を追加して動作確認
![S3を追加して動作確認](lecture05-img/s3.png)
- オブジェクトが保存されていることの確認
![オブジェクトの保存確認](lecture05-img/s3_object_storage.png)

## AWS構成図の作成
![AWS構成図](lecture05-img/aws_achitecture_diagram.png)

## 感想
課題を進める際、「今何の作業をしているのか」を常に意識しながら作業を進めました。講義で学んだ通り一つ一つの工程を細分化して進めることで、エラーが発生した際に原因箇所が明確になり、質問や検索がスムーズに行えました。  
課題を進める中で、原因不明の問題に直面し、EC2の再構築など、多くの時間を費やしてしまいましたが、その分深い学びを得ることができました。また、エラーを乗り越えたときの達成感は大きく、仮説検証を繰り返しながら解決するプロセスの重要性を再確認できました。