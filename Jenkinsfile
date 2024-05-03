pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Build ID'){
            steps{
                sh "echo $BUILD_ID"
            }
        }
        stage('Result'){
            steps{
                sh "echo $currentBuild.currentResult"
            }
        }
        
    }
}
