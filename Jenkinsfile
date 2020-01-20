pipeline {
     agent any
     stages {
           stage {'Clone Repo'}  {
           steps {
          sh "export AWS_DEFAULT_REGION=ap-south-1"
          sh "aws cloudformation create-stack --stack-name mydemostack5 --template-body file://S3Bucket.json --region 'ap-south-1"

          }
        }
      }
}
