# Kinesis
ストリーミングデータの収集・処理・リアルタイム分析に利用される。
SQSとの違いは福栖のコンシューマが**同時**に同じメッセージを取得され処理される点
## Kinesis Data Streams
ストリーミングデータをほぼリアルタイムで保存でき、EMRやLambdaなどの独自アプリケーションで処理することが可能
シャードで分割して並列処理を行う
## Kinesis Data Firehose
S3,Redshift,ESに簡単に配信・保存できる。
よくあるユースケースはS3やRedshiftにストリーミングデータを蓄積する
## Kinesis Data Analytics
ストリーミングデータに対し、SQLクエリを実行い、リアルタイム分析を行う。
