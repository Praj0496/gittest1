pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World. This is change frfom Gitbash'
            }
        }
        stage('Build ID'){
            steps{
              echo "Build ID is:"
              sh "echo $BUILD_ID"
            }
        }
        stage('Result'){
            steps{
             echo "The test result is:"
             sh "echo $currentBuild.currentResult"
            }
        }
        
    }
}
