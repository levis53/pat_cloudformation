pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation deploy --stack-name toto --template-body file://template-s3.json--region 'us-east-1'"
              }
             }
            }
            }
