pipeline {
    agent any
    environment {
      BUILD_NO=${BUILD_NUMBER}
    stages {
        stage('build') {
            echo "This is the build stage"
            steps {
                sh 'pwd'
            }
        }
        stage('test') {
            echo "This is the test stage"
            steps {
                sh 'pwd'
                sh 'echo $BUILD_NO'
            }
        }
    }
}
}
