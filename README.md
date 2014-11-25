#プッシュ通知スターター キット
本KitはWindows, iOS, Androidなどのアプリケーションに対して簡単にプッシュ通知を組み込むためのフレームワークです。アプリケーションの継続率や再帰率を向上させるために重要なプッシュ通知ですが、機能要件によっては実装が複雑で開発コストがかかります。このKitを用いることで開発者は大幅に開発コストを削減（サーバーサイドを実装することなく、クライアントサイドにいくつかのコードを追加するだけ）して、非常に簡単にスケーラブルで柔軟なプッシュ通知を実装することができます。


#特徴
###継続的に無償利用
独自にプッシュ通知を開発するには多くの実装やインフラストラクチャの構成が必要です。
このキットと Microsoft Azure を組み合わせることで無料で手軽にプッシュ通知をアプリに組み込むことができます。

###容易に導入
サーバー サイドのロジックは不要です。
また iOS、Android、Windows、Windows Phone 向けに SDK が提供されているため簡単に導入できます。

###タグによるターゲティング配信
任意の属性をもつユーザーだけに通知を配信できます。アプリの最終起動日時やユーザーの性別、年齢など組み合わせた条件を設定できます。
-たとえばサッカーに興味がある iOS ユーザーだけに配信
-東京在住の女性だけに広告を配信

###分析ツール
プラットフォーム毎に送信数や送信エラー数などの詳細なレポートが閲覧できます。

###スケジュール配信
指定した日や時間に配信予約することができます。


#ドキュメント

[利用方法の詳細](https://github.com/notificationkit/notificationkit/tree/master/docs).

KitはパブリッククラウドであるMicrosoft Azureのプッシュ通知サービスをベースに実装されています。プッシュ通知サービスにはリアルタイム大量配信、データ管理、サービス監視など便利な機能が予め実装されているので、開発者はプッシュ通知に関わる全ての機能を実装する必要がありません。またKitにはプッシュ通知を管理するための、Webポータルが含まれているので管理用UIを開発する必要もありません。
 
このKitを利用するためにはAzureアカウントの作成が必要です。Azureアカウントをお持ちでない開発者は、下記のサイトから作成してください。

Azure無料評価版

http://azure.microsoft.com/ja-jp/pricing/free-trial/

登録が完了すると以下のURLからAzure管理ポータルにアクセスできます。この管理ポータルからAzureの様々なサービスを利用することができます。

http://manage.windowsazure.com/


