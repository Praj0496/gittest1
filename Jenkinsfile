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
              echo 'Build ID is:'  sh "echo $BUILD_ID"
            }
        }
        stage('Result'){
            steps{
             echo 'The test result is:'   sh "echo $currentBuild.currentResult"
            }
        }
        
    }
}

