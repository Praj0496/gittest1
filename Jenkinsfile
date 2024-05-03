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
                'Build ID is' = sh "echo $BUILD_ID"
            }
        }
        stage('Result'){
            steps{
               'Result is' sh "echo $currentBuild.currentResult"
            }
        }
        
    }
}
