# Baseball Result Notifier

* Yahoo!の https://baseball.yahoo.co.jp/npb/ から1日1回結果を取得して、指定されたアドレスにメールを送信するスタックを作成します。
* Lambda, SNSは無料枠内、ClowdWatchは1円未満ほど。

[![Launch](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=ap-northeast-1#/stacks/new?stackName=baseball-result-notifier&templateURL=https://s3-ap-northeast-1.amazonaws.com/otamachan-cloudformation/baseball-result-notifier.template)