# lesson-for-docker

## CloudFormations

### iam

プロジェクトの管理ロールを作成する

### ecr

アプケーションのECRを構築する


:latest 146444637934.dkr.ecr.ap-northeast-1.amazonaws.com/hoge-fuga-pika-ecr-registory:1234


aws ecr get-login-password --profile hoge-fuga --region ap-northeast-1 | docker login --username AWS --password-stdin 146444637934.dkr.ecr.ap-northeast-1.amazonaws.com



