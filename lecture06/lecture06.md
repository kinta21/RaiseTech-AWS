# 第6回課題
## CloudTrail イベント履歴
- イベント名　　ModifyTemporaryCredentialsOnEnvironmentEC2 
- イベント情報（３つ）　イベント時間　イベントソース　ユーザー名  
![イベント履歴](lecture06-img/cloudtrail.png) 

## CloudWatch アラーム
- ### Rails アプリケーションが使える状態  
アラームが OK 状態になり、OK メールが通知される。
![アラームOK](lecture06-img/cloudtrail.png)  
  ![アラームOKメール](lecture06-img/cloudtrail.png)  
- ### Rails アプリケーションが使えない状態    
アラームがアラーム状態になり、ALARMメールが通知される。
![アラーム](lecture06-img/cloudtrail.png)  
![アラームメール](lecture06-img/cloudtrail.png)  

## AWS利用料金見積もり
- 今までに作成したリソースの見積もり  
URL:https://calculator.aws/#/estimate?id=423cb387b60adf3d08300558562f5773c450b81e

- 現在の利用料
![現在までの見積もり](lecture06-img/current-estimate.png)
- 先月のEC2 の料金
![先月のEC2 の料金](lecture06-img/cloudtrail.png)
- 無料利用枠で収まっているか  
アカウント作成から12カ月経過しているため、無料利用枠の対象外でした。