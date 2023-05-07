# lecture06について

### cloudtrailのログを確認して

イベント名,
DescribeAlarms(アラームの説明)

含まれている情報,
イベントが起きた時間,ユーザー名,発信元のIPアドレス


### cloudwatchアラーム設定について

・アプリケーションを起動した際のOKアクション
![ALBアクション確認](images06/ALB_OK.png)

紐づけたメールアドレスにOKアラートが通知されました。


・アプリケーションの起動を停止した際のアラート

![ALBアラート確認](images06/ALB_unhealthy.png)

紐づけたメールアドレスにunhealthyアラートが通知されました。


### 料金確認

先月のEC2インスタンスの料金
45.84円

今月はまだ無料期間枠に収まっています。


### 感想
cloudtrail、cloudwatchについて実際にサービスを扱ってみたり、ログを確認したことで今まで資格勉強の為に文字で覚えたサービスの理解を深めることができました。
見積書についてこういった書類を作成することも初なので少し手こずりました。自分で作成してきた環境について、無料枠を使用していることもあって実感が少し湧きづらかったですが、お金に換算すると結構かかっているんだなと思いました。