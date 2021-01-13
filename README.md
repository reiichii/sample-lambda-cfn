# CloudFormationでLambdaをデプロイするサンプルコード

Lambda: Python3.6

## todo

1. cfnのtemplate.yamlを埋める
   - {}の部分を環境に合わせて置き換えてください
2. lambda_function.pyをzipにまとめる
    - `zip SampleLambda lambda_function.py`
3. SampleLambda.zipを配置するS3バケットを作成し、zipファイルを配置
    - `aws s3 cp SampleLambda.zip s3://{Lambda用S3Bucket}`
4. cfnのスタックを作成し、テンプレートにtemplate.ymlを読み込ませる