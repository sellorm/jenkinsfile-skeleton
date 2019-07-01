pipeline {
    agent any
    environment {
      BUILD_NO="${BUILD_NUMBER}"
    }
    stages {
        stage('build') {
            steps {
                echo "This is the build stage"
                sh 'pwd'
            }
        }
        stage('test') {
            steps {
                echo "This is the test stage"
                sh 'pwd'
                sh 'echo ${BUILD_NO}'
            }
        }
    }
}
