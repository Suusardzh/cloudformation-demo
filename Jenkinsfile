pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3bucket --template-body http://ec2-jenkins --region 'us-east-1'"
              }
             }
            }
            }
