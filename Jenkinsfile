pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name ec2 --template-body file://template-s3.json--region 'us-east-1'"
              }
             }
            }
            }
