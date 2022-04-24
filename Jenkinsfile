pipeline {
    agent any
    tools {nodejs "mynodejs"}
    stages {
        stage('Dev') {
            steps {
                git 'https://github.com/srj6675/aws_codebuild_codedeploy_nodeJs_demo.git'
                echo "check below"
                sh 'cat index.js'
            }
        }
        stage('build') {
            steps {
               sh 'npm install'
            }
        }        
    }
}