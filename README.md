# CloudFormationを学習した時の記録

## AWS CLIで動作させる

実行コマンド

スタックを作成する
```
aws cloudformation create-stack --template-body file:///[リポジトリまでのパス]/study-cloudformation/rails-tutorial-template.yaml --stack-name cfn-rails-tutorial
```

スタックを削除する
```
aws cloudformation delete-stack --stack-name cfn-rails-tutorial
```

テンプレートの構文チェック
```
aws cloudformation validate-template --template-body file:///[リポジトリまでのパス]/study-cloudformation/rails-tutoria
l-template.yaml
```

* VPC、EC2、RDSなどの環境

rails-tutorial-template.yaml

* ALB

rails-tutorial-template-alb.yaml

## TODO

