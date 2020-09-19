pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name ec-2bucket --template-body file://ec2-jenkins --region 'us-east-1'"
              }
             }
            }
            }
